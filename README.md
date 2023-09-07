
![Next js Roadmap - Frame 1](https://github.com/Blazity/nextjs-roadmap/assets/28964599/093f913d-9254-472b-86c3-8d75782a9b62)

1. Fundamentals:
    1. **React**
    2. **Typescript**
       1. [ts-reset](https://github.com/total-typescript/ts-reset) - a CSS reset for TypeScript, improving types for common JavaScript API's
    4. **Next.js** (similar frameworks: [Hydrogen](https://hydrogen.shopify.dev/), [Gatsby](https://www.gatsbyjs.com/), [Remix](https://remix.run/))

2. Rendering Techniques:
    1. **[Streaming](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming)**
    2. **[SSG](https://nextjs.org/docs/pages/building-your-application/rendering/static-site-generation)** (Static Site Generation)
    3. **[SPR](https://vercel.com/blog/serverless-pre-rendering)** (Serverless Pre-rendering)
    4. **[ISR](https://nextjs.org/docs/pages/building-your-application/data-fetching/incremental-static-regeneration)** (Incremental Static Regeneration)
        1. Fixed
        2. [On-demand](https://nextjs.org/docs/pages/building-your-application/data-fetching/incremental-static-regeneration#using-on-demand-revalidation)
    6. **[CSR](https://nextjs.org/docs/pages/building-your-application/rendering/client-side-rendering)** (Client-Side Rendering)
    7. **[SSR](https://nextjs.org/docs/pages/building-your-application/rendering/server-side-rendering)** (Server-Side Rendering)
    8. **[Preview Mode](https://nextjs.org/docs/pages/building-your-application/configuring/preview-mode)**
  
3. Styling & UI:
    1. Preprocessors:
        1. [Sass](https://sass-lang.com/)
        2. [PostCSS](https://postcss.org/)
        3. [Less](https://lesscss.org/)
    3. CSS in JS:
        1. [Emotion](https://emotion.sh/docs/introduction)
        2. [Styled Components](https://styled-components.com/)
        3. [Styled System](https://github.com/styled-system/styled-system)
        4. [Vanilla Extract](https://vanilla-extract.style/)
        5. [Linaria](https://github.com/callstack/linaria)
        6. [CSS Modules](https://github.com/css-modules/css-modules)
        7. [TailwindCSS](https://tailwindcss.com/)
    5. Component Libraries:
        1. [radix-ui](https://www.radix-ui.com/)
        2. [antd](https://ant.design/) 
        3. [nextui](https://nextui.org/)
        4. [ariakit](https://ariakit.org/)
        5. [react-spectrum](https://react-spectrum.adobe.com/react-spectrum/)
        6. [mui](https://mui.com/)
        7. [daisyui](https://daisyui.com/)
        8. [chakra](https://chakra-ui.com/)
        9. [fluentui](https://developer.microsoft.com/en-us/fluentui#/)
        10. [mantine](https://mantine.dev/)
        11. [headlessui](https://headlessui.com/)
4. Routers:
    1. [App Router](https://nextjs.org/docs/app)
        1. [Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components)
        2. [Client Components](https://nextjs.org/docs/app/building-your-application/rendering/client-components)
        3. [Layouts](https://nextjs.org/docs/app/building-your-application/routing/pages-and-layouts)
    3. [Pages Router](https://nextjs.org/docs/pages)
5. Performance
    1. Hydration
        1. [Progressive Hydration](https://www.patterns.dev/posts/progressive-hydration)
        2. [Selective Hydration](https://www.patterns.dev/posts/react-selective-hydration)
        3. [Resumability](https://qwik.builder.io/docs/concepts/resumable/)
    2. [next/image](https://nextjs.org/docs/pages/api-reference/components/image)
    3. [next/script](https://nextjs.org/docs/pages/api-reference/components/script)
    4. [next/font](https://nextjs.org/docs/pages/api-reference/components/font)
    5. [BundleAnalyzer](https://www.npmjs.com/package/webpack-bundle-analyzer)
    6. [Partytown](https://partytown.builder.io/)
6. Deployment
    1. Hosting
        1. [Vercel](https://vercel.com/)
        2. [GCP](https://blog.logrocket.com/how-to-deploy-next-js-on-google-cloud-run/)
        3. [AWS](https://docs.aws.amazon.com/amplify/latest/userguide/deploy-nextjs-app.html)
        4. [Netlify](https://www.netlify.com/)
        5. [Azure](https://learn.microsoft.com/en-us/azure/static-web-apps/deploy-nextjs-hybrid)
        6. [Cloudflare](https://developers.cloudflare.com/pages/framework-guides/deploy-a-nextjs-site/)
        7. [Railway](https://docs.railway.app/getting-started)
        8. [Render](https://render.com/docs/deploy-nextjs-app)
        9. [Fly.io](https://fly.io/docs/js/frameworks/nextjs/)
        10. [Digital Ocean ](https://docs.digitalocean.com/developer-center/deploy-a-next.js-app-to-app-platform/)
    2. CDN
        1. [Cloudflare](https://www.cloudflare.com/application-services/products/cdn/)
        2. [CloudFront](https://aws.amazon.com/cloudfront/)
        3. [KeyCDN](https://www.keycdn.com/)
        4. [AzureCDN](https://azure.microsoft.com/en-us/products/cdn/)
        5. [CloudCDN](https://cloud.google.com/cdn)
        6. [Fastly](https://www.fastly.com/products/cdn)
        7. [Akamai](https://www.akamai.com/solutions/content-delivery-network)    
    3. [MultiZones](https://nextjs.org/docs/pages/building-your-application/deploying/multi-zones)
    4. IaC
        1. [SST.dev](https://sst.dev/)
        2. [Pulumi](https://www.pulumi.com/)
        3. [Terraform](https://www.terraform.io/)
7. State Management
    1. [Zustand](https://github.com/pmndrs/zustand)
    2. [Context API](https://react.dev/reference/react/createContext)
    3. [Jotai](https://jotai.org/)
    4. [Redux Toolkit](https://redux-toolkit.js.org/)
    5. [Recoil](https://recoiljs.org/)
    6. [XState](https://xstate.js.org/)
    7. [MobX](https://mobx.js.org/README.html)
8. Bundlers
    1. [Webpack](https://webpack.js.org/)
    2. [Turbopack](https://turbo.build/pack)
9. Testing
    1. E2E
        1. [Playwright](https://playwright.dev/)
        2. [Cypress](https://www.cypress.io/)
        3. [TestCafe](https://testcafe.io/)
    2. Unit
        1. [Jest](https://jestjs.io/)
        2. [Vitest](https://vitest.dev/) 
    3. Integration
        1. [React Testing Library ](https://testing-library.com/docs/react-testing-library/intro/)
    4. Visual
        1. [StoryBook](https://storybook.js.org/)
        2. [Docz](https://www.docz.site/)
        3. [React Styleguidist](https://react-styleguidist.js.org/)
        4. [React Cosmos](https://reactcosmos.org/)
10. API Communication
    1. REST
        1. [TanStack Query](https://tanstack.com/query/latest)(works with GraphQL too)
        2. [SWR](https://swr.vercel.app/)  (works with GraphQL too)
    2. GraphQL
        1. [Apollo](https://www.apollographql.com/)
        2. [Relay](https://relay.dev/)
        3. [URQL](https://formidable.com/open-source/urql/)
        4. [Graphql-request](https://www.npmjs.com/package/graphql-request)
    3. Web Sockets
        1. [Socket.io](https://socket.io/)
        2. [Ably](https://ably.com/)
        3. [Convex](https://www.convex.dev/)
        4. [Pusher](https://vercel.com/guides/deploying-pusher-channels-with-vercel)
        5. [PubNub](https://www.pubnub.com/)
        6. [Firebase Realtime Database](https://firebase.google.com/docs/database)
        7. [Supabase](https://supabase.com/realtime)
    4. [Api Routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes) / [Route Handlers](https://nextjs.org/docs/app/building-your-application/routing/route-handlers)
    5. gRPC
    6. [tRPC](https://trpc.io/docs/client/nextjs/setup)
11. i18n
    1. [next-translate](https://github.com/aralroca/next-translate)
    2. [lingui](https://lingui.dev/)
    3. [i18next](https://react.i18next.com/)
    4. [react-intl](https://github.com/formatjs/formatjs)
12. Architecture
    1. Modular
    2. [Feature-Sliced Design](https://feature-sliced.design/)
    3. Monorepo
        1. [Turborepo](https://turbo.build/)
        2. [NX](https://nx.dev/)
        3. [Lerna](https://lerna.js.org/)
    4. Monolith
13. SEO
    1. [next-seo](https://github.com/garmeeh/next-seo)
    2. [@vercel/og](https://vercel.com/docs/functions/edge-functions/og-image-generation)
14. Auth
    1. [NextAuth](https://next-auth.js.org/)
    2. [IronSession](https://github.com/vvo/iron-session)
    3. [Passport](https://www.passportjs.org/)
15. Observability
    1. [OpenTelemetry](https://opentelemetry.io/)
    2. [DataDog](https://vercel.com/integrations/datadog)https://vercel.com/integrations/datadog
    3. [New Relic](https://github.com/newrelic/newrelic-node-nextjs)https://github.com/newrelic/newrelic-node-nextjs
    4. [Sentry](https://docs.sentry.io/platforms/javascript/guides/nextjs/)https://docs.sentry.io/platforms/javascript/guides/nextjs/  
