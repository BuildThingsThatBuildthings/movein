# File Naming Conventions & Organization Standards

## Overview
Standardized naming conventions ensure consistent organization, easy searchability, and seamless coordination between all 9 specialized agents in the senior transition management system.

## Universal Naming Format

### Standard Structure
```
YYYY-MM-DD_[CATEGORY]_[description]_[version]_[STATUS].[extension]
```

### Components Explanation
- **YYYY-MM-DD**: Date in ISO format for chronological sorting
- **CATEGORY**: 3-4 letter category code (see Category Codes below)
- **description**: Descriptive name using hyphens instead of spaces
- **version**: Version control using semantic versioning (v1.0, v1.1, v2.0)
- **STATUS**: Document status indicator (see Status Codes below)
- **extension**: File type (.pdf, .docx, .xlsx, .png, etc.)

## Category Codes

### Primary Categories
- **MED**: Medical & Health documents
- **LEG**: Legal & Estate documents  
- **FIN**: Financial & Investment documents
- **HOME**: Home Modifications documents
- **LIFE**: Lifestyle & Social documents
- **PURP**: Purpose & Legacy documents
- **COORD**: Coordination & Communication documents

### Specialized Subcategories
- **MED-RX**: Medications and prescriptions
- **MED-CARE**: Care plans and protocols
- **MED-INS**: Insurance and healthcare coverage
- **LEG-EST**: Estate documents and wills
- **LEG-POA**: Power of attorney documents
- **FIN-BUD**: Budget and expense tracking
- **FIN-INV**: Investment and portfolio documents
- **HOME-MOD**: Home modifications and assessments
- **HOME-EQUIP**: Equipment and assistive devices
- **LIFE-ACT**: Activities and recreation
- **LIFE-TRANS**: Transportation and mobility
- **PURP-LEG**: Legacy projects and family history
- **COORD-FAM**: Family communication and meetings

## Status Codes

### Document Status Indicators
- **DRAFT**: Working document, not yet finalized
- **REVIEW**: Under review by family members or professionals
- **FINAL**: Completed and approved document
- **ARCHIVED**: Historical document, superseded by newer version
- **TEMPLATE**: Standard template for recurring document types

### Version Control Standards
- **v1.0**: Initial complete version
- **v1.1, v1.2**: Minor revisions and corrections
- **v2.0**: Major revisions or significant changes
- **v3.0+**: Substantial updates or complete rewrites

## Naming Examples

### Medical Documents
- `2024-01-15_MED_primary-care-visit_Dr-Johnson_v1.0_FINAL.pdf`
- `2024-01-20_MED-RX_metformin_prescription-update_v2.1_REVIEW.pdf`
- `2024-01-25_MED-CARE_daily-routine_morning-protocol_v1.0_FINAL.docx`
- `2024-01-30_MED-INS_medicare_enrollment-confirmation_v1.0_FINAL.pdf`

### Legal Documents
- `2024-02-01_LEG_will_final-testament_v3.0_FINAL.pdf`
- `2024-02-05_LEG-POA_healthcare_power-of-attorney_v1.0_FINAL.pdf`
- `2024-02-10_LEG-EST_trust_revocable-living-trust_v2.0_REVIEW.pdf`
- `2024-02-15_LEG_attorney-consultation_Smith-Law-estate-review_v1.0_FINAL.docx`

### Financial Documents
- `2024-02-20_FIN_monthly-budget_February_v1.0_FINAL.xlsx`
- `2024-02-25_FIN-BUD_care-costs_projection-analysis_v1.1_REVIEW.xlsx`
- `2024-03-01_FIN-INV_portfolio-review_quarterly-assessment_v1.0_DRAFT.pdf`
- `2024-03-05_FIN_insurance_long-term-care-policy_v1.0_FINAL.pdf`

### Home Modification Documents
- `2024-03-10_HOME-MOD_accessibility-assessment_bathroom-evaluation_v1.0_FINAL.pdf`
- `2024-03-15_HOME_contractor-quote_ramp-installation_ABC-Construction_v1.0_REVIEW.pdf`
- `2024-03-20_HOME-EQUIP_medical-equipment_hospital-bed-delivery_v1.0_FINAL.docx`
- `2024-03-25_HOME_permit_bathroom-modification_city-approval_v1.0_FINAL.pdf`

### Lifestyle & Social Documents
- `2024-04-01_LIFE-ACT_exercise-program_senior-fitness-class_v1.0_FINAL.pdf`
- `2024-04-05_LIFE-TRANS_transportation-schedule_medical-appointments_v2.0_FINAL.xlsx`
- `2024-04-10_LIFE_volunteer-opportunity_community-center_application_v1.0_REVIEW.pdf`
- `2024-04-15_LIFE_social-calendar_April-activities_v1.0_FINAL.docx`

### Purpose & Legacy Documents
- `2024-04-20_PURP-LEG_family-history_grandmother-stories_v1.0_DRAFT.docx`
- `2024-04-25_PURP_memoir-writing_chapter-1_childhood-memories_v2.1_REVIEW.docx`
- `2024-05-01_PURP_volunteer-work_literacy-program_training-materials_v1.0_FINAL.pdf`
- `2024-05-05_PURP_goal-setting_quarterly-objectives_Q2-2024_v1.0_FINAL.docx`

### Coordination & Communication Documents
- `2024-05-10_COORD-FAM_family-meeting_care-plan-discussion_v1.0_FINAL.docx`
- `2024-05-15_COORD_progress-report_monthly-summary_May-2024_v1.0_FINAL.pdf`
- `2024-05-20_COORD_agent-communication_priority-update_urgent_v1.0_FINAL.txt`
- `2024-05-25_COORD_emergency-protocol_contact-list-update_v3.0_FINAL.pdf`

## Folder Organization Rules

### Folder Naming Standards
- Use lowercase letters with underscores for spaces
- Keep folder names descriptive but concise (maximum 25 characters)
- Use consistent terminology across all categories
- Maintain hierarchical organization with clear parent-child relationships

### File Quantity Limits
- Maximum 20 files per folder before creating subfolders
- Use date-based subfolders for high-volume categories (YYYY-MM format)
- Create subject-based subfolders for different document types
- Archive older files to maintain current folder usability

### Cross-Reference Standards
- Use consistent naming for related documents across categories
- Include reference numbers or identifiers for related document sets
- Maintain relationship documentation for complex multi-category projects
- Create index files for large document collections

## Special Naming Situations

### Scanned Documents
- `2024-01-15_MED_handwritten-notes_Dr-visit_scanned_v1.0_FINAL.pdf`
- Include "scanned" identifier for physical document conversions
- Maintain original date if known, otherwise use scan date
- Include source description for handwritten or historical documents

### Multi-Part Documents
- `2024-01-15_LEG_will_final-testament_part-1-of-3_v1.0_FINAL.pdf`
- `2024-01-15_LEG_will_final-testament_part-2-of-3_v1.0_FINAL.pdf`
- `2024-01-15_LEG_will_final-testament_part-3-of-3_v1.0_FINAL.pdf`
- Include part numbering for documents split across multiple files
- Maintain consistent base naming across all parts

### Sensitive Documents
- `2024-01-15_LEG_SSN-tax-info_[ENCRYPTED]_v1.0_FINAL.pdf.enc`
- Add [ENCRYPTED] identifier for encrypted sensitive documents
- Use .enc extension for encrypted files
- Maintain separate access log for sensitive document handling

### Template Documents
- `TEMPLATE_MED_appointment-log_standard-format_v2.0_TEMPLATE.docx`
- Begin with "TEMPLATE" prefix for reusable document formats
- Include template version for template management
- Use TEMPLATE status for easy identification

## Quality Control Checklist

### Before Saving Any Document
- [ ] Date is in YYYY-MM-DD format
- [ ] Correct category code is used
- [ ] Description uses hyphens, not spaces
- [ ] Version number follows semantic versioning
- [ ] Status code is appropriate for document state
- [ ] File extension matches actual file type

### File Organization Verification
- [ ] Document is saved in correct category folder
- [ ] Folder contains fewer than 20 files (create subfolder if needed)
- [ ] Related documents use consistent naming patterns
- [ ] No duplicate files with different names
- [ ] Archive older versions when new final version is created

### Security and Access Verification
- [ ] Sensitive documents are properly encrypted
- [ ] Access permissions are correctly set
- [ ] Backup procedures have been followed
- [ ] Document is properly referenced in coordination systems

---

**Maintained by**: data-organization-agent  
**Last Updated**: 2024  
**Version**: 1.0  
**Review Schedule**: Quarterly updates and improvements