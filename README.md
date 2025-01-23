# WordsUnspoken

WordsUnspoken is an anonymous letter-sharing platform where users can express themselves freely through letters, create conversation chains, and share moments through images. The platform emphasizes privacy while fostering meaningful connections through written expression.

## 🌟 Features

### Core Functionality
- **Anonymous Letter Creation**: Write and share letters without identity
- **Letter Reading**: Explore letters in an elegant, card-based interface
- **Letter Chains**: Reply to letters and create meaningful conversation threads
- **Media Support**: Attach images to letters (max 500KB)
- **Scheduled Posting**: Choose when your letter becomes visible
- **Random Discovery**: Find random letters through our shuffle feature

### Technical Features
- Responsive design for all devices
- Real-time data updates using Firebase
- Image hosting via Cloudinary
- Smooth animations and transitions
- Emotion-based color coding for letters

## 🔧 Technologies Used

- HTML5
- CSS3
- JavaScript
- Firebase (Backend & Database)
- Cloudinary (Image Storage)
- Netlify (Hosting)


## 💾 Database Structure

```javascript
letters/
  ├── letterId/
  │   ├── title: string
  │   ├── content: string
  │   ├── timestamp: datetime
  │   ├── scheduledTime: datetime
  │   ├── emotion: string
  │   ├── imageUrl: string?
  │   ├── likes: number
  │   ├── parentLetterId: string?
  │   └── isVisible: boolean
```

## 📱 Responsive Design

The application is fully responsive with breakpoints:
- Mobile: 320px - 480px
- Tablet: 481px - 768px
- Desktop: 769px and above

## 🔒 Privacy & Security

- All letters are anonymous by default
- No user authentication required
- Image size restricted to 500KB
- Content moderation through Firebase security rules

## 🚧 Future Enhancements

- [ ] Improved Database
- [ ] Letter categories/tags
- [ ] Android app
- [ ] Report inappropriate content feature
- [ ] Letter statistics and trending topics


## ✨ Acknowledgments

- Inspiration from traditional letter writing
- Community feedback and suggestions
