# Hotels XML Schema Project

assignment 4 about xml to better understand the basics of it including XML schemas, validation, and transformation
This project includes one XML Schema file and two XML example files.  
They show how hotel data can be structured and validated using XML and XSD.

---

## Files

### **Hotels.xsd**
- Defines the structure and rules for the hotel XML data.  
- Includes elements like `<Hotel>`, `<Name>`, `<Phone>`, and `<Address>` with required and optional attributes.

### **Hotels.xml**
- A **valid example** that follows all the rules in `Hotels.xsd`.  
- Contains 11 real hotels, with some having multiple phone numbers.

### **HotelsErrors.xml**
- A **broken version** of `Hotels.xml` made to test validation errors.  
- Includes 5 problems: wrong root tag, missing attribute, missing phone, unclosed tag, and duplicate names.

---
