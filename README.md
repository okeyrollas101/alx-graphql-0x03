# Query the graphql endpoint

This was achieved using the useQuery hook to query/request data from the `graphql/queries`- `GET_EPISODE` file which takes a second args variables an object
that alters thae `page`. The exact data that is required is being fetched and displayed thereby eliminating over-fetching or under-fetching and increasing
overall application performance.
