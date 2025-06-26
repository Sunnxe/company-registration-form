# Company Registration Form

A comprehensive web-based company registration form with PDF generation capabilities, built for GatherEase AI.

## Features

- ✅ **Complete Registration Form**: Company details, shareholders, directors, managers, and authorized signers
- ✅ **Dynamic Form Elements**: Add/remove shareholders, directors, and signers as needed
- ✅ **File Upload Support**: Upload required documents (PDF, JPG, PNG)
- ✅ **PDF Generation**: Generate professional PDF summary with all form data
- ✅ **Mobile Responsive**: Optimized for both desktop and mobile devices
- ✅ **Chinese Language Support**: Full Traditional Chinese interface
- ✅ **Form Validation**: Built-in validation for required fields and shareholding percentages

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **PDF Generation**: jsPDF + html2canvas
- **Styling**: Custom CSS with responsive design
- **File Handling**: FileReader API for document uploads

## Getting Started

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd register
   ```

2. Open `index.html` in a web browser or serve it with a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

3. Navigate to `http://localhost:8000` (if using a server) or open `index.html` directly

## File Structure

```
register/
├── index.html          # Main application file
├── logo.png           # Company logo
├── README.md          # Project documentation
└── .gitignore         # Git ignore rules
```

## Form Sections

1. **Company Basic Information** (公司基本資料)
   - Company name (English/Chinese)
   - Registered capital
   - Business scope
   - Registered address (with HGM address service option)

2. **Shareholders Information** (股東資料)
   - Dynamic shareholder addition/removal
   - Shareholding percentage validation (must total 100%)
   - Document upload for each shareholder

3. **Directors Information** (公司董事)
   - Select from existing shareholders or add external directors
   - Document upload for external directors

4. **Manager Information** (負責人資料)
   - Select from directors or add external manager
   - Document upload for external managers

5. **Authorized Signers** (授權簽字人)
   - Single or joint signature authorization
   - Select from directors or add external signers

## Document Requirements

### For Taiwanese Citizens
- Passport copy (signed by the person)

### For Thai Citizens
- ID card copy + Household registration copy (signed by the person)

### For Other Nationalities
- Passport copy (signed by the person)

### For Corporate Entities
- Company registration certificate + Responsible person ID documents

## PDF Generation

The application generates a comprehensive PDF document containing:
- All form data in organized sections
- List of uploaded documents with file names and sizes
- Professional formatting with company branding
- Generation timestamp

## Mobile Optimization

The form is fully responsive and optimized for mobile devices:
- Card-based layout for better readability
- Full-width inputs for easier interaction
- Vertical stacking of form elements
- Touch-friendly buttons and controls

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is proprietary software developed for GatherEase AI.

## Support

For questions or support, please contact the development team.

---

*Generated with GatherEase AI*