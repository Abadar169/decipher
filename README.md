# Next.js Project Learnings

## Learnings

1. **Setting up a Next.js Project:**
   To set up a Next.js project, follow the official [Next.js documentation](https://nextjs.org/docs/getting-started).

2. **Basic Folder Structure:**
   The basic folder structure typically includes folders such as `pages`, `components`, `styles`, `public`, etc. The `pages` folder is crucial for Next.js as it defines the routes for the application.

3. **Setting up Routes and Routing:**
   Routes in Next.js are defined based on the file structure within the `pages` directory. Each file in the `pages` directory corresponds to a route.

4. **Dynamic Routes:**
   Dynamic routes in Next.js allow you to create pages with variable paths. You can utilize the brackets `[]` to define dynamic segments in the URL.

5. **Next Navigation Hook:**
   The Next.js `useRouter` hook from `next/router` allows you to access the router object, enabling navigation within your application.

6. **Difference between Client and Server Component:**
   - **Client Components:** Client components are traditional React components that are bundled and executed on the client-side. They're suitable for interactive and dynamic user interfaces.
   - **Server Components:** Server components are rendered on the server-side, offering better performance and server-side rendering capabilities. They can fetch data asynchronously within the component itself.

7. **Fetching Data Asynchronously in Server Components:**
   Server components in Next.js can fetch data asynchronously within the component itself using functions like `getServerSideProps` or `getStaticProps`. This helps in fetching data on the server and passing it to the component during server-side rendering.

## Usage

Follow these steps to use the project and apply the learnings:

1. Clone the repository: `git clone <repository_url>`
2. Navigate to the project directory: `cd <project_directory>`
3. Install dependencies: `npm install`
4. Run the development server: `npm run dev`

Feel free to explore the code and experiment with the concepts mentioned in the learnings section.
