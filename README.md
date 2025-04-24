# eBird Hotspot Radius

eBird Hotspot Radius is a web application that provides a user-friendly interface for interacting with the eBird API. It simplifies making requests to the eBird API's 25 endpoints, allowing users to explore bird observation data, taxonomy, regions, and more.

## Features

- **Observation Data**: Fetch recent observations, notable observations, and species-specific data for regions or locations.
- **Taxonomy**: Explore taxonomic information about bird species, including categories, scientific names, and family details.
- **Regions**: Retrieve information about regions, subregions, and hotspots.
- **Checklists**: View and analyze checklists submitted on specific dates or for specific regions.
- **Sorting and Filtering**: Customize API requests with parameters like date, distance, species, and more.
- **Data Formats**: Supports CSV and JSON formats for API responses.

## Project Structure

The project is organized as follows:

```
.
├── public/
│   ├── vite.svg
├── src/
│   ├── components/       # Reusable UI components
│   ├── hooks/            # Custom React hooks for API interactions
│   ├── pages/            # Page components for different API endpoints
│   ├── services/         # API client and endpoint-specific hooks
│   ├── store/            # Redux store and slices
│   ├── types/            # TypeScript type definitions
│   ├── utilities/        # Utility functions
│   ├── main.tsx          # Application entry point
├── .eslintrc.cjs         # ESLint configuration
├── .prettierrc.json      # Prettier configuration
├── package.json          # Project dependencies and scripts
├── tsconfig.json         # TypeScript configuration
├── vite.config.ts        # Vite configuration
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or later)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:

```sh
git clone https://github.com/katrinaclow/kc-ebird-api-ui.git
cd kc-ebird-api-ui
```

2. Install dependencies:

```sh
npm install
```

### Running the Application

Start the development server:

```sh
npm run dev
```

The application will be available at [http://localhost:3000](http://localhost:3000).

### Building for Production

To build the application for production:

```sh
npm run build
```

The production-ready files will be in the `dist/` directory.

### Linting and Formatting

To lint the code:

```sh
npm run lint
```

To format the code with Prettier:

```sh
npm run format
```

## Contributing

This project is a fork of the original [eBird API UI](https://github.com/Fimbelowski/ebird-api-ui) created by [Christopher Fimbel](https://github.com/Fimbelowski). Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Links

- **Live Demo**: [eBird API UI](https://ebird-api-ui.com/)
- **GitHub Repository**: [kc-ebird-api-ui](https://github.com/katrinaclow/kc-ebird-api-ui)
- **Original Repository**: [eBird API UI by Christopher Fimbel](https://github.com/Fimbelowski/ebird-api-ui)
- **eBird API Documentation**: [eBird API](https://documenter.getpostman.com/view/664302/ebird-api-20/2HTbHW)

---
Built by [Katrina Clow](https://github.com/katrinaclow), based on the original work by [Christopher Fimbel](https://github.com/Fimbelowski).
