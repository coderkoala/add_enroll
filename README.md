# Add Enroll

### Augments Program Enrollment

---

- Adds fields sales invoice, customer into Program Enrollment
- Allows for generation of sales invoice instead of using the fee structure JV entry
- Is completely optional and noninstrusive to the original software.
- Adds field "item" to Fee Category and Courses, so they can be used in Sales Invoice
- Note the new functionality ignores fee categories or courses that have no item assigned.

---

### Installation

Navigate to your site's bench directory, use the following commands 
    
    bench get-app add_enroll https://github.com/coderkoala/add_enroll
    bench install-app add_enroll
    bench migrate
    
In case of a multi tenant system, simply add
    
    --site <Your_Site_Name>

---

#### License

MIT

Made in behalf of The Open Institute.
