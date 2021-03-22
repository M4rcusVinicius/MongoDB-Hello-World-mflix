## My first database ( using MongoDB )

This app get movies data in MongoDB and use Next js to display. I'm folwing the tutorial [How to Integrate MongoDB Into Your Next.js App](https://developer.mongodb.com/how-to/nextjs-with-mongodb/). If you're interesing to start a db, I recomended this tutorial !

If you want to learn more about MongoDB, visit the following pages:

- [MongoDB Atlas](https://mongodb.com/atlas)
- [MongoDB Documentation](https://docs.mongodb.com/)

### Set up environment variables

Copy the `env.local.example` file in this directory to `.env.local` (which will be ignored by Git):

```bash
cp .env.local.example .env.local
```

Set each variable on `.env.local`:

- `MONGODB_URI` - Your MongoDB connection string. If you are using [MongoDB Atlas](https://mongodb.com/atlas) you can find this by clicking the "Connect" button for your cluster.
- `MONGODB_DB` - The name of the MongoDB database you want to use.

