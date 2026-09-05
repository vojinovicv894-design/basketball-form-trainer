# Basketball Form Trainer

An AI-powered basketball training app that analyzes and rates your shooting form using computer vision, providing personalized workout plans based on your age, height, and weight.

## Features

- **Personalized Workout Generation**: Create custom training plans based on your physical profile (age, height, weight) and experience level
- **Black & Blue Theme**: Sleek dark interface with blue accents for an engaging user experience
- **Experience Levels**: Beginner, Intermediate, Advanced, and Elite training programs
- **Detailed Exercise Breakdown**: Each workout includes specific exercises with sets, reps, and timing
- **AI Form Analysis**: Video-based shooting form analysis (upcoming feature)
- **Progress Tracking**: Monitor your improvement over time

## Getting Started

### Prerequisites

- Node.js 16+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/vojinovicv894-design/basketball-form-trainer.git
cd basketball-form-trainer
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Tech Stack

- **Next.js 14**: React framework for production
- **Tailwind CSS**: Utility-first CSS framework
- **React Hooks**: State management with useState

## Project Structure

```
basketball-form-trainer/
├── app/
│   ├── layout.js          # Root layout
│   ├── globals.css        # Global styles
│   └── page.js            # Home page
├── components/
│   ├── WorkoutForm.js     # User input form
│   └── WorkoutPlan.js     # Workout display
├── tailwind.config.js     # Tailwind configuration
├── next.config.js         # Next.js configuration
└── package.json           # Dependencies
```

## Usage

1. **Enter Your Profile**: Start by entering your age, height (in cm), and weight (in kg)
2. **Select Experience Level**: Choose from Beginner, Intermediate, Advanced, or Elite
3. **Generate Workout**: Click "Generate Workout Plan" to receive your personalized training plan
4. **View Details**: Review exercises, sets, reps, and timing recommendations
5. **Train**: Follow the workout and film yourself for AI form analysis (coming soon)

## Workout Customization

The app generates workouts based on:

- **Age**: Adjusts intensity and duration appropriately
- **BMI**: Factors in fitness level for safer training
- **Experience**: Tailors exercises to skill level
- **Height/Weight**: Personalizes exercise recommendations

## Planned Features

- 📹 AI-powered video form analysis using computer vision
- ⭐ Form rating system (0-100 scale)
- 📊 Progress tracking and statistics
- 📱 Mobile app version
- 🎯 Custom drill creation
- 🔄 Real-time feedback during shooting
- 📈 Performance analytics

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.

## Contact

For questions or feedback, reach out to the development team.

---

**Start training smarter today! 🏀**
