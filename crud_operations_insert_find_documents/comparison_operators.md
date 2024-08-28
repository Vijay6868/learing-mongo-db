##### db.movies.find({"tomatoes.viewer.numReviews":{$lte: 65}})

  type: 'movie',
  tomatoes: {
    viewer: {
      rating: 4,
      numReviews: 64,
      meter: 50
    },
    lastUpdated: 2015-06-12T19:17:52.000Z
  },
  num_mflix_comments: 0

##### db.movies.find({"tomatoes.viewer.rating":{$lt: 3}})

type: 'movie',
  tomatoes: {
    viewer: {
      rating: 0,
      numReviews: 0
    },
    lastUpdated: 2015-01-09T01:44:51.000Z
  }

#### db.movies.find({"tomatoes.viewer.rating":{$gt:2.0}})

  type: 'movie',
  tomatoes: {
    viewer: {
      rating: 3.8,
      numReviews: 3
    },
    lastUpdated: 2015-07-16T17:59:55.000Z
  },
  num_mflix_comments: 0

#### db.movies.find({"tomatoes.viewer.numReviews": {$exists: true}})

  type: 'movie',
  tomatoes: {
    viewer: {
      rating: 2.5,
      numReviews: 2
    },
    lastUpdated: 2015-05-02T19:03:48.000Z
  }