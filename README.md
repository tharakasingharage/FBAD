# LFC Technology Risk Maturity Assessment

A web-based assessment tool for evaluating technology risk maturity in Licensed Finance Companies (LFCs) based on the **Finance Business Act Directions No. 01 of 2022** issued by the Central Bank of Sri Lanka.

## Overview

This application helps LFCs assess their technology risk management capabilities across six key domains:

1. **Technology Risk Governance and Oversight** (4.1-4.5)
2. **Information and Information System Security** (5.1-5.11)
3. **Information System Availability and Disaster Recovery** (6.1-6.5)
4. **Staff Competency Requirements** (7.1)
5. **Third Party Service Provider Management** (8.1-8.9)
6. **Cloud Services** (9.1-9.6)

## Features

- 📊 **Real-time Scoring**: Automatic calculation of maturity scores as you complete assessments
- 📈 **Dashboard**: Visual overview of overall maturity score and assessment completeness
- 🎯 **Maturity Scale**: 6-level maturity model (Not Started → Optimized)
- 📝 **Detailed Tracking**: Track implementation status, evidence, comments, and gap analysis
- 💾 **Export to Excel**: Download assessment results as CSV for reporting and documentation
- 📱 **Responsive Design**: Works on desktop, tablet, and mobile devices
- 🔒 **Privacy-First**: All data stays in your browser - nothing is sent to servers

## Maturity Levels

| Level | Label | Description |
|-------|-------|-------------|
| 0 | Not Started | No initiatives in place |
| 1 | Initial | Ad-hoc processes, reactive approach |
| 2 | Developing | Basic processes established |
| 3 | Defined | Documented and standardized processes |
| 4 | Managed | Measured and controlled processes |
| 5 | Optimized | Continuous improvement culture |

## How to Use

### Getting Started

1. **Open the Application**
   - Simply open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari)
   - No installation or server required

2. **Complete the Assessment**
   - Expand each section by clicking on the section header
   - For each control item:
     - Select a **Maturity Level** (0-5)
     - Choose an **Implementation Status**
     - Add **Evidence/Documentation** references
     - Include **Comments** for context
     - Document **Gap Analysis & Remediation Plans**

3. **Monitor Progress**
   - View real-time scores in the dashboard
   - Track assessment completeness percentage
   - Review section-by-section performance

4. **Export Results**
   - Click the "Export to Excel" button
   - Download a CSV file with all responses
   - Open in Excel, Google Sheets, or any spreadsheet application

### Assessment Sections

#### 1. Technology Risk Governance and Oversight (9 controls)
Board oversight, risk management framework, CISO appointment, and internal audit compliance.

#### 2. Information and Information System Security (18 controls)
Data classification, access management, encryption, SOC, DLP, incident response, and security testing.

#### 3. Information System Availability and Disaster Recovery (4 controls)
System availability targets, DR arrangements, activation triggers, and testing.

#### 4. Staff Competency Requirements (1 control)
Qualifications for security, risk, and audit functions.

#### 5. Third Party Service Provider Management (7 controls)
Oversight, assessment, SLAs, regulatory compliance, and data protection.

#### 6. Cloud Services (6 controls)
Risk understanding, assessment, configuration, certifications, and data protection.

## Technical Details

### Technologies Used
- **React 18** - UI framework
- **TailwindCSS** - Styling
- **Babel Standalone** - JSX compilation in browser
- **HTML5/CSS3** - Core web technologies

### Browser Compatibility
- Chrome 90+
- Firefox 90+
- Safari 14+
- Edge 90+

### Data Storage
- All assessment data is stored temporarily in browser memory
- Data is lost when the page is refreshed or closed
- Use the Export feature to save your progress

## Compliance Reference

This tool is based on:
- **Finance Business Act Directions No. 01 of 2022**
- Issued by: Monetary Board, Central Bank of Sri Lanka
- Effective Date: January 1, 2023
- Focus: Technology Risk Management and Resilience

## File Structure

```
/workspace
├── index.html          # Main application (single-file React app)
└── README.md           # This documentation file
```

## Limitations

- ⚠️ **No Persistent Storage**: Data is not saved between sessions. Always export your work.
- ⚠️ **Single User**: Designed for individual use, not multi-user collaboration.
- ⚠️ **Browser-Based**: Requires JavaScript enabled in your browser.

## Best Practices

1. **Regular Assessments**: Conduct assessments quarterly or bi-annually
2. **Document Evidence**: Keep detailed records of policies, procedures, and implementations
3. **Track Gaps**: Use the gap analysis field to plan improvements
4. **Export Frequently**: Save your progress regularly using the Export feature
5. **Review Scores**: Use maturity scores to prioritize remediation efforts

## Support

For questions about the regulatory requirements:
- Contact: Central Bank of Sri Lanka
- Reference: Finance Business Act Directions No. 01 of 2022

For technical issues with this tool:
- Check browser console for errors (F12 → Console)
- Ensure you're using a supported browser
- Clear browser cache if experiencing issues

## License

This tool is provided as-is for educational and compliance purposes. Users are responsible for ensuring accurate assessments and regulatory compliance.

---

**Version**: 1.0  
**Last Updated**: 2024  
**Compliance Framework**: Finance Business Act Directions No. 01 of 2022, Central Bank of Sri Lanka
