# VitalBite: AI-Powered Calorie Tracker

A modern, intelligent calorie tracking application that uses Google's Gemini AI to accurately identify and calculate calories for any food item, whether through text descriptions or images.

🌐 **Live App**: [VitalBite](https://vitalbite.netlify.app/)

## Key Features

### AI-Powered Food Recognition
- **Text-Based Analysis**: Accurately identify and calculate calories from food descriptions
- **Image Recognition**: Upload food images for automatic identification and calorie calculation
- **Cultural Awareness**: Supports various cuisines with proper recognition of regional food names
- **Smart Portion Detection**: Automatically detects and accounts for serving sizes

### User Experience
- **Real-Time Processing**: Instant food recognition and calorie calculation
- **Smart Loading States**: Intuitive loading overlays during AI processing
- **Responsive Design**: Works seamlessly across desktop and mobile devices
- **Error Handling**: Graceful error handling with helpful user feedback

### Data Management
- **Search History**: Track and revisit recent food searches
- **Food History**: Maintain a comprehensive history of tracked foods
- **Caching System**: 
  - Preflight caching for API optimization
  - Food description caching
  - Calorie calculation caching
  - Image processing results caching

### Security Features
- **API Key Management**: Secure handling of API keys with encryption
- **User Authentication**: Secure user accounts via Supabase
- **Data Privacy**: Encrypted storage of sensitive information
- **Key Rotation**: Support for API key rotation during high load

### Smart Features
- **Portion Recognition**: Automatically detects serving sizes from descriptions
- **Regional Food Support**: Specialized handling of various cuisines
- **Nutritional Accuracy**: AI-powered precise calorie calculations
- **Food Validation**: Ensures accurate food identification before processing

## Technical Stack

### Frontend
- React with TypeScript
- Tailwind CSS for styling
- Framer Motion for animations
- Shadcn UI components

### AI & APIs
- Google Gemini AI for food recognition
- Custom AI prompts for accurate results
- Optimized API calls with retry mechanisms
- Intelligent caching system

### Backend & Storage
- Supabase for authentication and data storage
- Local storage for caching and preferences
- Encrypted data storage for sensitive information

### Performance Features
- Exponential backoff for API retries
- Preflight request caching
- Optimized image processing
- Smart state management

## Security

- Encrypted API key storage
- Secure user authentication
- Protected API endpoints
- Rate limiting and request validation
- Secure data transmission

## Use Cases

1. **Quick Food Logging**
   - Type food descriptions for instant calorie information
   - Upload food images for automatic recognition
   - Get accurate portion-based calculations

2. **Dietary Tracking**
   - Track daily calorie intake
   - Review food history
   - Monitor eating patterns

3. **Cultural Food Support**
   - Recognition of regional food names
   - Support for various cuisines
   - Accurate portion size detection

4. **Professional Use**
   - Nutritionists can quickly calculate calories
   - Restaurants can verify calorie information
   - Fitness trainers can help clients track intake

## License

This project is licensed under the MIT License - see the LICENSE file for details.
