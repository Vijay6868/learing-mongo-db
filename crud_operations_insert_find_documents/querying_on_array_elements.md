#### db.movies.find({"cast":"Lois Wilson"})

  _id: ObjectId('573a1391f29313caabcd71e3'),
  plot: 'Wlliam deMille produced and directed Miss Lulu Bett, a film of extraordinary conviction and insight. It was then often the custom for unmarried women to lodge with family; thus we discover ...',
  genres: [
    'Comedy',
    'Drama'
  ],
  runtime: 71,
  cast: [
    'Lois Wilson',
    'Milton Sills',
    'Theodore Roberts',
    'Helen Ferguson'
  ],
  num_mflix_comments: 0,
  poster: 'https://m.media-amazon.com/images/M/MV5BMTY5MTY0MzY0Ml5BMl5BanBnXkFtZTgwNjE4NDAxMjE@._V1_SY1000_SX677_AL_.jpg',
  title: 'Miss Lulu Bett',
  fullplot: 'Wlliam deMille produced and directed Miss Lulu Bett, a film of extraordinary conviction and insight. It was then often the custom for unmarried women to lodge with family; thus we discover Miss Lulu in a boring Midwestern town, an exploited household drudge for her sister and her overbearing brother-in-law. In the course of the story (based upon the Pulitzer Prize play and novel by Zona Gale), Lulu evolves from slavery into an attractive and self-assured woman, prepared to make her own life. Revealed through wonderful performances and clever use of props, the characters are extraordinarily solid and involving.',
  countries: [
    'USA'
  ],
  released: 1921-11-01T00:00:00.000Z,
  directors: [
    'William C. de Mille'
  ],
  writers: [
    'Clara Beranger (adaptation)',
    'Zona Gale (novel)'
  ],
  awards: {
    wins: 1,
    nominations: 0,
    text: '1 win.'
  },
  lastupdated: '2015-08-21 00:15:46.140000000',
  year: 1921,
  imdb: {
    rating: 7.2,
    votes: 204,
    id: 12465
  },
  type: 'movie',
  tomatoes: {
    viewer: {
      rating: 2.5,
      numReviews: 2
    },
    lastUpdated: 2015-05-02T19:03:48.000Z
  }

  #### db.movies.find({genres:	{$elemMatch: {$eq: "Drama"}}})
  _id: ObjectId('573a1391f29313caabcd8521'),
  plot: 'The son of the sheik and a dancing girl fall in love, but when he is made to believe she has betrayed him he seeks revenge.',
  genres: [
    'Adventure',
    'Drama'
  ],
  runtime: 68,
  rated: 'PASSED',
  cast: [
    'Rudolph Valentino',
    'Vilma Bènky',
    'George Fawcett',
    'Montagu Love'
  ],
  poster: 'https://m.media-amazon.com/images/M/MV5BNzY0MWQwNjQtMzg1YS00ZWQzLTlhMWMtNTU2ZTUxZDZlNTRlXkEyXkFqcGdeQXVyNjc0MzMzNjA@._V1_SY1000_SX677_AL_.jpg',
  title: 'The Son of the Sheik',
  fullplot: "Men and women, fathers and children. Ahmed, son of Diana and Sheik Ahmed Ben Hassan, falls in love with Yasmin, a dancing girl who fronts her father's gang of mountebanks. Among the cutthroats is Ghobah, a villainous Moor to whom Yasmin is promised. In ruins near Touggourt, the city where Yasmin dances, she and Ahmed meet secretly until one night when her father and the gang capture the son of the sheik, torture him, and hold him for ransom. Will Ahmed believe that Yasmin set him up for capture? Even if true love finds a way through webs of deceit, what will the vigorous and imposing sheik say about his son consorting with a dancing girl?",
  languages: [
    'English'
  ],
  released: 1926-09-05T00:00:00.000Z,
  directors: [
    'George Fitzmaurice'
  ],
  writers: [
    'Edith Maude Hull (based on the novel by)',
    'Frances Marion (screen adaptation)',
    'Fred De Gresac (screen adaptation)',
    'George Marion Jr. (titles)'
  ],
  awards: {
    wins: 1,
    nominations: 0,
    text: '1 win.'
  },
  lastupdated: '2015-08-28 00:55:59.283000000',
  year: 1926,
  imdb: {
    rating: 7.5,
    votes: 1339,
    id: 17416
  },
  countries: [
    'USA'
  ],
  type: 'movie',
  tomatoes: {
    viewer: {
      rating: 3.5,
      numReviews: 81,
      meter: 62
    },
    fresh: 5,
    critic: {
      rating: 6.9,
      numReviews: 7,
      meter: 71
    },
    rotten: 2,
    lastUpdated: 2015-07-01T19:58:21.000Z
  },
    num_mflix_comments: 0
