### Setup Node Environment

You'll need to create a new node server. Open a new terminal within the project directory and run:

1. Initialize a new project: `npm i`
2. run the development server with `npm run dev`

### Create a new endpoint in the server.ts file

The starter code has a task for you to complete an endpoint in `./src/server.ts` which uses query parameter to download an image from a public URL, filter the image, and return the result.

We've included a few helper functions to handle some of these concepts and we're importing it for you at the top of the `./src/server.ts`  file.

```typescript
import {filterImageFromURL, deleteLocalFiles} from './util/util';
```

### Deploying your system

`eb init` a new application and `eb create` a new environment to deploy your image-filter service! Don't forget you can use `eb deploy` to push changes.

## Base URL

http://image-filter-dev2.us-east-1.elasticbeanstalk.com/filteredimage?image_url={{}}

## Live demo:

http://image-filter-dev2.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://lh3.googleusercontent.com/DlvyUR7l83VSV09kfKpzDPAcTVvpnCt7VhzkB51krY_WnIt4CGyXvJrT5WY5YjtVBrxccm5MZfLV9MFdVapY1qDOG7oVdO8HqLmJf_lMuSGY7-jYDON43jG5pR1RsiXmg2kTTA1XIXYIqK28wppLq9-LysYqvYcXAm17KrN4N2V650mbVItk2NNADz3X7uuiJrw00OKylqRlPmo6kvZHZ-mx2gOKOBSKhEhLkKb5m2Fg4EtoNQIhUYNG31LVupioRa4sTXi9AcsHsEyeeOWARcgVUs8WWi8c0niYItrm4mhrqTj0XSBdlre8MOWPjOrnc8bgJtl7bqKSF3fK6reedke6YEyOaxLDBZDzrOJQ2KA1WN9oXuPQL7LuBA_MuK0JUtwphvKRiUhK-TLCXyjkLQT859p5SJ9BeRfQNXlnPfBpmSOfB7JiHMqUWopj4Xkcu962g15kCEoEYAQcpAOSHMxdObPwjbjoBpPj69A_HmMO4E8B1kaCoZcYlycBv2ZYkh8Y8-V9i30R9AhQoRF2tJJd_Y-G37Ue5ljvBhl_9aEm791CF2H1H_hoenGyvwnP02xuFUUlYW6krpe4lJtS7tBqJoe4E0dLfSmwicn9934aP9AvSuc4TmI3g0Gf6Y33BCVNFYyyaqLZ2AQXiyQqyq_HAmICxM7w4O8jozloaf8gBndHBz7KWIc4XItbkg=w2156-h1616-no
