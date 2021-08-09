# Deployment

## Vercel (Recommended)

> **The easiest way to deploy Next.js to production is to use the Vercel platform from the creators of Next.js. Vercel is an all-in-one platform with Global CDN supporting static & Jamstack deployment and Serverless Functions.**

## Getting started

1. _Sign up to Vercel._

2. _After signing up, you’ll arrive on the “Import Project” page. Under “From Git Repository”, choose the Git provider you use and set up an integration. (Instructions: `GitHub` / `GitLab` / `BitBucket`)._

3. _After importing, it’ll deploy your Next.js app and provide you with a deployment URL. Click “Visit” to see your app in production._

## Workflow to use. Vercel supports

> _what we call the DPS workflow: `Develop`, `Preview`, and `Ship`._

**Develop**: Write code in Next.js. Keep the development server running and take advantage of React Fast Refresh.

**Preview**: Every time you push changes to a branch on GitHub / GitLab / BitBucket, Vercel automatically creates a new deployment with a unique URL. You can view them on GitHub when you open a pull request, or under “Preview Deployments” on your project page on Vercel.

**Ship**: When you’re ready to ship, merge the pull request to your default branch (e.g. main). Vercel will automatically create a production deployment.

# ElephantSQL

> _ElephantSQL installs and manages PostgreSQL databases for you._

## Database in the Cloud

> _ElephantSQL offers databases ranging from shared servers for smaller projects and proof of concepts, up to enterprise-grade multi-server setups._

###### Follower (HA) plans

> _In the face of hardware or software failure of the master node, ElephantSQL will make an automatic failover to the follower on all HA (high availability) plans. The follower can be located in another region or even at a different cloud provider._
