#### db.movies.aggregate([{$sort:{pop:-1}}],{$limit: 3})

{
  _id: ObjectId('573a1390f29313caabcd4803'),
  plot: 'Cartoon figures announce, via comic strip balloons, that they will move - and move they do, in a wildly exaggerated style.',
  genres: [
    'Animation',
    'Short',
    'Comedy'
  ],
  runtime: 7,
  cast: [
    'Winsor McCay'
  ],
  num_mflix_comments: 0,
  poster: 'https://m.media-amazon.com/images/M/MV5BYzg2NjNhNTctMjUxMi00ZWU4LWI3ZjYtNTI0NTQxNThjZTk2XkEyXkFqcGdeQXVyNzg5OTk2OA@@._V1_SY1000_SX677_AL_.jpg',
  title: 'Winsor McCay, the Famous Cartoonist of the N.Y. Herald and His Moving Comics',
  fullplot: 'Cartoonist Winsor McCay agrees to create a large set of drawings that will be photographed and made into a motion picture. The job requires plenty of drawing supplies, and the cartoonist must also overcome some mishaps caused by an assistant. Finally, the work is done, and everyone can see the resulting animated picture.',
  languages: [
    'English'
  ],
  released: 1911-04-08T00:00:00.000Z,
  directors: [
    'Winsor McCay',
    'J. Stuart Blackton'
  ],
  writers: [
    'Winsor McCay (comic strip "Little Nemo in Slumberland")',
    'Winsor McCay (screenplay)'
  ],
  awards: {
    wins: 1,
    nominations: 0,
    text: '1 win.'
  },
  lastupdated: '2015-08-29 01:09:03.030000000',
  year: 1911,
  imdb: {
    rating: 7.3,
    votes: 1034,
    id: 1737
  },
  countries: [
    'USA'
  ],
  type: 'movie',
  tomatoes: {
    viewer: {
      rating: 3.4,
      numReviews: 89,
      meter: 47
    },
    lastUpdated: 2015-08-20T18:51:24.000Z
  }
}



#### db.movies.aggregate([{$project:{genres:0, cast:0, tomatoes:0}}])

{
  _id: ObjectId('573a1391f29313caabcd70b4'),
  plot: 'An extended family split up in France and Germany find themselves on opposing sides of the battlefield during World War I.',
  runtime: 150,
  rated: 'PASSED',
  num_mflix_comments: 1,
  poster: 'https://m.media-amazon.com/images/M/MV5BOTU1ODQyYTctODhkNy00YWRmLWE2YzYtMTQ5ZjA3OTNiN2QyXkEyXkFqcGdeQXVyMzE0MjY5ODA@._V1_SY1000_SX677_AL_.jpg',
  title: 'The Four Horsemen of the Apocalypse',
  fullplot: 'Julio Madariaga is the Argentine patriarch of a wealthy family. He has two daughters, the elder wed to a Frenchman and the other to a German. He prefers the Frenchman and his family, especially his grandson Julio, causing jealousy from the German and his three sons. When Madariaga dies, the family splits up, each son-in-law returning to his own country. The Frenchman and his own move to Paris, where Julio becomes an artist and has an affair with an unhappily married woman, the lovely Marguerite Laurier. Her husband finds out, but before he can finalize a divorce, World War One rears its head and both sides of the family will endure great suffering in the conflict, especially since they must fight one another on the battlefield.',
  countries: [
    'USA'
  ],
  released: 1923-03-31T00:00:00.000Z,
  directors: [
    'Rex Ingram'
  ],
  writers: [
    'Vicente Blasco Ibèèez (novel)',
    'June Mathis (written for the screen by)'
  ],
  awards: {
    wins: 1,
    nominations: 0,
    text: '1 win.'
  },
  lastupdated: '2015-08-24 00:59:30.430000000',
  year: 1921,
  imdb: {
    rating: 7.9,
    votes: 2475,
    id: 12190
  },
  type: 'movie'
}

#### db.movies.aggregate([{$count: "total_movies"}])
{
  total_movies: 21349
}