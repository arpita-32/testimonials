# Testimonial Carousel

A simple and responsive testimonial carousel built using **React** and **Tailwind CSS**. This project displays user reviews dynamically and allows navigation between testimonials using left/right buttons or a "Surprise Me" button for random selection.

## Features
- Display user testimonials with name, job title, image, and quote.
- Left and right buttons to navigate between testimonials.
- "Surprise Me" button to randomly display a testimonial.
- Responsive and aesthetically pleasing UI using **Tailwind CSS**.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/testimonial-carousel.git
   ```
2. Navigate to the project directory:
   ```bash
   cd testimonial-carousel
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```

## Project Structure
```
.
├── src
│   ├── components
│   │   ├── Card.js         # Renders individual testimonials
│   │   ├── Testimonial.js  # Controls testimonial navigation
│   ├── App.js              # Main component
│   ├── index.js            # Entry point
├── public
│   ├── index.html          # HTML template
├── package.json            # Project dependencies and scripts
├── tailwind.config.js      # Tailwind CSS configuration
├── README.md               # Project documentation
```

## Usage
1. Add your testimonial data in the `reviews` array and pass it as props to the `Testimonial` component.
2. The testimonial component will render and allow users to navigate through the testimonials.

## Dependencies
- **React** (Frontend framework)
- **Tailwind CSS** (Styling)
- **React Icons** (Icons for navigation and quotes)

## Screenshots
![Testimonial Carousel Screenshot](https://via.placeholder.com/800x400.png?text=Screenshot+Placeholder)

## Contributing
Feel free to contribute to this project! Fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the **MIT License**.

## Author
[Your Name](https://github.com/your-username)

