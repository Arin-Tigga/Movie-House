# MovieHouse - Movie Recommendation App

A modern, responsive web application that helps users discover and explore movies using The Movie Database (TMDB) API. Built with React.js, this app provides an intuitive interface for searching, filtering, and browsing movies with detailed information.

## 🎬 Features

- **Movie Search**: Search for movies by title using the TMDB API
- **Advanced Filtering**: Filter movies by genre and sort by various criteria
- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Movie Details**: View movie posters, titles, ratings, and descriptions
- **Expandable Descriptions**: Click "Read More" to see full movie descriptions
- **Real-time Updates**: Dynamic content updates based on search and filter selections

### Sorting Options
- Popularity (Descending/Ascending)
- Rating (Descending/Ascending)
- Release Date (Descending/Ascending)

### Genre Filtering
- Filter by all available movie genres from TMDB
- Option to view all genres or select specific ones

## 🚀 Getting Started

### Prerequisites
- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Movie-Recommendation-App-main
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to view the application

## 🛠️ Available Scripts

- `npm start` - Runs the app in development mode
- `npm build` - Builds the app for production
- `npm test` - Launches the test runner
- `npm eject` - Ejects from Create React App (one-way operation)

## 📱 Usage

1. **Search Movies**: Use the search bar to find movies by title
2. **Apply Filters**: Use the dropdown menus to sort and filter movies
3. **Browse Results**: Scroll through the movie grid to discover new films
4. **View Details**: Click "Read More" to expand movie descriptions
5. **Responsive Navigation**: The app adapts to different screen sizes automatically

## 🎨 Design Features

- **Modern UI**: Clean, card-based design with smooth animations
- **Color Scheme**: Dark theme with contrasting elements
- **Typography**: Custom fonts (Anta, Poppins, Teko) for enhanced readability
- **Grid Layout**: Responsive grid system that adapts to screen size
- **Hover Effects**: Interactive elements with smooth transitions

## 🔧 Technical Stack

- **Frontend Framework**: React.js 18.2.0
- **HTTP Client**: Axios for API requests
- **Icons**: React Icons library
- **Routing**: React Router DOM
- **Styling**: CSS3 with responsive design
- **API**: The Movie Database (TMDB) API

## 📁 Project Structure

```
Movie-Recommendation-App-main/
├── public/
│   ├── index.html
│   ├── favicon.ico
│   └── manifest.json
├── src/
│   ├── components/
│   │   ├── MovieApp.js      # Main application component
│   │   └── MovieApp.css     # Component styles
│   ├── App.js              # Root application component
│   ├── App.css             # Global styles
│   ├── index.js            # Application entry point
│   └── index.css           # Global CSS
├── package.json            # Dependencies and scripts
└── README.md              # This file
```

## 🌐 API Integration

The app integrates with The Movie Database (TMDB) API to fetch:
- Movie search results
- Movie discovery with filters
- Genre information
- Movie posters and metadata

**API Endpoints Used:**
- `https://api.themoviedb.org/3/search/movie` - Search movies
- `https://api.themoviedb.org/3/discover/movie` - Discover movies with filters
- `https://api.themoviedb.org/3/genre/movie/list` - Get genre list

## 📱 Responsive Design

The application is fully responsive with breakpoints for:
- **Desktop**: 5-column grid layout
- **Tablet**: 3-column grid layout
- **Mobile**: 2-column grid layout
- **Small Mobile**: 1-column grid layout

## 🎯 Key Features Implementation

### Search Functionality
- Real-time search with debounced API calls
- Search results update dynamically
- Clear search input with intuitive UI

### Filtering System
- Genre-based filtering with dropdown selection
- Multiple sorting options for different preferences
- Combined filtering and sorting capabilities

### Movie Display
- Movie posters with fallback handling
- Rating display with styled badges
- Truncated descriptions with expand/collapse functionality
- Responsive image handling

## 🔒 Environment Variables

The app currently uses a hardcoded API key for demonstration purposes. For production use, consider:
- Moving the API key to environment variables
- Implementing proper API key management
- Adding rate limiting and error handling

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- [The Movie Database (TMDB)](https://www.themoviedb.org/) for providing the movie data API
- [React Icons](https://react-icons.github.io/react-icons/) for the icon library
- [Google Fonts](https://fonts.google.com/) for the typography

## 📞 Support

If you encounter any issues or have questions, please:
1. Check the existing issues in the repository
2. Create a new issue with detailed information
3. Include steps to reproduce the problem

---

**Happy Movie Watching! 🎬🍿**
