# Work & Rise - East African Freelance Marketplace

Work & Rise is a freelancer marketplace dedicated to the economic empowerment of all Ugandans - visit https://workandrise.com for more information.

This public repository for Work & Rise details the work I did, especially on the mobile application. This was the first major dev project of my career, and so understandably, some rookie mistakes were made.

The core technologies used were React on the front-end, mostly with class components. It was deployed on a Cloudfront distribution, in the EU zone for better connectivity to East Africa. Hooks were not yet a thing, can you believe that?! I used a Node.js server with Express middleware to run a Sequelize instance (an SQL, Postgres specifically, ORM where you define schemas and queries in JS) that was deployed on AWS using the Elastic Container Service. This was augmented by some serverless functions tying into a payment API called Beyonic, which would allow our users to transact directly in Ugandan shillings. This was the MVP I was hired to build.

At this point, my involvement in the business waned - I moved on to work on some other projects, though I always kept in touch to provide some immediate bug fixes or advice. The other developer, Esau, is a great guy & incredibly hard working. Over the next year or so, they updated the front-end a lot to account for new wallet functionality, and totally migrated the backend ORM to a Python backend, in addition to a hand-rolled admin portal. The admin tools offered by Beyonic were unreliable, for our purposes.

At the beginning of 2021, I started talking with my old colleagues and contributed a quick mobile application with React Native to help them increase their velocity. It is now live on the Play Store. They had been using a responsive web application, which is great, but a mobile app provides a more stable, simpler experience for the unique challenges of the East African market.