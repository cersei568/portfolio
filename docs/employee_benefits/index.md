# 💼 Benefits Selection Assistant

A luxury-themed, multi-language benefits enrollment system.

![Main Interface](assets/bea0.png)  

👉 Try the app: **[Demo Link (Streamlit)](https://benefits.streamlit.app)**  
👉 Explore the code: **[GitHub Repository](https://github.com/cersei568/benefits_enrollment_assistant)**  

The Benefits Selection Assistant is a sophisticated web application designed to streamline the benefits enrollment process for organizations. Built with Streamlit and featuring a luxury design aesthetic, this portal provides employees with an intuitive interface to explore, compare, and select their benefits packages.

---

## Features

### 📊 Dashboard
- Real-time benefits status overview
- Selected plans summary with cost breakdowns
- Interactive cost visualization charts
- Budget tracking and salary percentage calculations

### 📋 Plan Comparison
- Side-by-side comparison of all available benefit plans
- Coverage tier selection (Employee, Employee + Partner, Employee + Children, Family)
- Detailed plan specifications and coverage details
- Employer contribution percentage display

### ✅ Benefits Selection
- Intuitive radio button selection for each benefit category
- Real-time cost calculations as you select
- Three-metric display: Your Contribution, Employer Contribution, Net Cost
- Confirmation workflow to prevent accidental submissions

### 👨‍👩‍👧‍👦 Dependent Management
- Add family members (spouse, children, partners)
- Document verification tracking
- Secure data storage with masked IDs
- Edit and remove dependents functionality

### 📄 Documents Center
- Organized document categories
- One-click download functionality
- Policy documents, handbooks, and guides
- Upload capability for verification documents

### 📈 Analytics
- 6-month cost projection charts
- Benefits utilization tracking
- Personalized optimization recommendations
- Savings opportunity calculator

### 🌐 Multi-Language Support
- English (en)
- Polish (pl)
- German (de)
- Easy language switching in top navigation
- Complete UI translation including all labels and messages

---

## Usage

### For Employees

1. **Select Language**: Choose your preferred language from the dropdown in the top-right corner
2. **Review Dashboard**: Check your current benefits status and selections
3. **Compare Plans**: Navigate to the Comparison tab to view all available benefit plans
4. **Make Selections**: Go to Benefits Selection tab and choose your desired plans
5. **Add Dependents**: If covering family members, add them in the Dependents tab
6. **Confirm**: Review your selections and confirm to complete enrollment

### For HR Administrators

1. **Customize Plans**: Edit benefit plan details in the `medical_plans`, `sport_plans`, and `insurance_plans` lists
2. **Adjust Costs**: Modify premium amounts, deductibles, and employer contribution percentages
3. **Update Translations**: Add or modify text in the `TRANSLATIONS` dictionary
4. **Configure Theme**: Adjust colors and styling in the CSS section

---

## Security Considerations

- **Data Encryption**: Implement encryption for sensitive employee data
- **Authentication**: Add user authentication (e.g., OAuth, SAML)
- **Session Management**: Secure session state management
- **HTTPS**: Always use HTTPS in production
- **Input Validation**: Validate all user inputs
- **Rate Limiting**: Implement rate limiting for API endpoints

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


![Main Interface](assets/bea1.png)

![Main Interface](assets/bea2.png)

![Main Interface](assets/bea3.png)