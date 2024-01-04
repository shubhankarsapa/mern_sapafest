# SapaFest | Full-Stack MERN Application
## Introduction 
Introducing SapaFest, a dynamic full-stack MERN application built atop the powerful Next.js 14 framework, designed to redefine the realm of event management and participation. SapaFest emerges as a global epicenter for a diversity of events, offering an intuitive platform that facilitates seamless Stripe payment integrations for ticket purchases. Whether you're looking to attend the most talked-about events or orchestrate your own, SapaFest provides the tools and technology to bring people together, transforming the art of event engagement across the globe.

## Tech Stack
- Node.js
- Next.js
- TypeScript
- TailwindCSS
- Stripe
- Zod
- React Hook Form
- Shadcn
- uploadthing

## Features
▻ **Streamlined User Management with Clerk:** Our platform harnesses Clerk for robust user management, offering secure and streamlined sign-up, sign-in, and user profile functionalities.

▻ **Full-Spectrum Event Management:** Users are equipped with complete control to craft, peruse, refine, and remove events(CRUD)

- **Create:** Initiate events with ease, detailing the essentials like title, date, venue, and more.
  
- **Discover:** Access a curated catalogue of events, diving into comprehensive descriptions and itineraries.
  
- **Update:** Modify existing events to keep information current and relevant.
  
- **Delete:** Maintain the platform's integrity by removing outdated listings.

▻ **Related Events Discovery:** Enhance user engagement by smartly linking related events on each event detail page.

▻ **User-Centric Event Organization:** Events are neatly arranged, presenting a tailored view on user profiles for the events they've created.

▻ **Advanced Search & Filtering:** A powerful search engine paired with versatile filtering tools allows users to pinpoint events that cater to their unique tastes.

▻ **Seamless Category Expansion:** Add new event categories with zero hassle, ensuring the platform stays dynamic and ever-evolving.

▻ **Stripe-Powered Payments:** Checkout is a breeze with Stripe's secure payment gateway, ensuring a smooth transactional experience.

▻ **Order Oversight:** A detailed order tracking system offers users a transparent view of their event-related transactions.

▻ **Expedited Order Search:** Quickly locate and manage orders with an efficient search feature.

And that's not all — this platform is also built with an eye towards code elegance and reusability, making it a robust foundation for future enhancements.

## Live Project 
See SapaFest in action [HERE](https://mern-sapafest.vercel.app/) or on https://mern-sapafest.vercel.app/

## Quick Start Guide
Follow these steps to set up and run the project locally on your machine.

### Prerequisites
Make sure you have the following installed on your machine:
- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/)
- [npm](https://npmjs.com/) (Node Package Manager)

### Cloning the Repository
```bash
git clone https://github.com/your-username/your-project.git
cd your-project
```

### Installation
Install the project dependencies using npm:
```bash
npm install
```

### Set Up Environment Variables 
Create a new file named .env in the root of your project and add the following content:
```bash
#NEXT
NEXT_PUBLIC_SERVER_URL=

#CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_CLERK_WEBHOOK_SECRET=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

#MONGODB
MONGODB_URI=

#UPLOADTHING
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

#STRIPE
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
```
Replace the placeholder values with your actual credentials

### Running the Project
```bash
npm start 
or
npm run dev
```
Open http://localhost:3000 in your browser to view the project.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
