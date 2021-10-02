## TODOs

### POC
 - [ ] Setup Workbox
 - [ ] Setup API connection to Airtable
 - [ ] Create Airtable Schema
 - [ ] Render images from Airtable in slider with timed transition based on atomic clock

### V1
 - [ ] Add Galleries
   - [ ] CRUD
   - [ ] Only Gallery owners can assign an airtable table to a gallery
   - [ ] Add optional passcode to joining gallery
 - [ ] Add Device groups
   - Add device to a group and assign a gallery for the group to render, each device in the group is than given a unique order of images to show. 
   - This means multiple device groups can render the same gallery around the world
   - [ ] CRUD
   - [ ] Only group owners can add new devices to a group
## Dev

```bash
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## API routes
[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/*](http://localhost:3000/api/*).

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.
