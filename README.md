# Influencer and Sponsorship Platform

## Description

This platform connects sponsors and influencers, allowing sponsors to get their products or services advertised through influencers, while influencers benefit monetarily. It simplifies the process of discovering potential partnerships, managing deals, and tracking the outcomes of sponsorships.

## Features

- **Sponsor-Influencer Matching**: Helps sponsors find influencers that align with their brand, audience, and marketing goals.
- **Sponsorship Management**: Tools for managing deals, from initial contact through to campaign completion and payment.
- **Payment Integration**: Enables secure transactions between sponsors and influencers.
- **Analytics**: Provides insights on campaign performance, helping both parties assess ROI.
- **Messaging**: In-platform communication system for sponsors and influencers to negotiate and collaborate.
- **User-friendly Interface**: Simple and intuitive UI/UX for easy navigation and use.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (for front-end development)
- [Django](https://www.djangoproject.com/) (for back-end development)
- [TypeScript](https://www.typescriptlang.org/) (for front-end scripting)
- Database (PostgreSQL)

### Backend Installation (Django)

1. Clone the repository:
   ```bash
   git clone https://github.com/T-Naveen-2308/Influencer-and-Sponsorship-Platform.git
   cd influencer-sponsorship-platform/backend
   ```

2. Set up a virtual environment and activate it:
   ```bash
      python -m venv env
      source env/bin/activate  # On Windows: `env\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Ensure you create a `.env` file in the root directory of your project with the following environment variables:

   ```plaintext
   DATABASE_NAME=your_database_name   # Name of your database
   DATABASE_USER=your_username        # Username for the database
   DATABASE_PASSWORD=your_password    # Password for the database user
   DATABASE_HOST=your_hostname        # Host where the database is located
   DATABASE_PORT=your_port            # Port for the database connection
   ```


5. Run migrations to set up the database:
   ```bash
   python manage.py migrate
   ```

6. Create a superuser for admin access:
   ```bash
   python manage.py createsuperuser
   ```

7. Start the Django development server:
   ```bash
   python manage.py runserver
   ```

### Frontend Installation (React.js with TypeScript)

1. Navigate to the frontend folder:
   ```bash
   cd ../frontend
   ```

2. Install the required Node.js dependencies:
   ```bash
   npm install
   ```

3. Set up your .env file for the React front-end, including the API URL and other environment variables.
   ```plaintext
   VITE_API_BASE_URL=your_base_url #Base URL of Backend API
   ```

4. Start the React development server:
   ```bash
   npm start
   ```

## Usage

### For Sponsors
- Sponsors can create an account.
- Browse through available influencers.
- Send sponsorship offers.

### For Influencers
- Influencers can set up their profiles.
- Showcase their reach and audience.
- Respond to sponsorship offers.

### Deal Tracking
- Once a deal is made, both parties can:
  - Track its progress through the platform.
  - Monitor campaign performance.
  - Manage payments.


## Contributing

We welcome contributions! Please follow these steps to contribute:

1. Fork the project.
   
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```

3. Commit your changes:
   ```bash
   git commit -m 'Add feature'
   ```

4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
   
5. Open a pull request.

## Contact

If you have any questions or need assistance, feel free to reach out to us at [naveentummala033@gmail.com](mailto:naveentummala033@gmail.com).
