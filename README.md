# Next.js Runtime Error in Production: Accessing Undefined Environment Variable

This repository demonstrates a common runtime error in Next.js applications when accessing environment variables in production that are not defined.  The issue arises when the `about.js` component attempts to access `process.env.MY_SECRET_VAR` which is not set in the production environment.