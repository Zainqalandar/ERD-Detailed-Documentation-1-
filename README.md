

## 🧩 Entities & Attributes

### **1. Farmer List**
- **Attributes**: 
  - Expected Price
  - Quantity
  - Harvest Date

### **2. Buyers**
- **Attributes**:
  - Bid
  - Purchase

### **3. Crops**
- **Attributes**:
  - Grades

### **4. Logistics Partners**
- **Attributes**:
  - Disputes
  - Weather Warning

### **5. Quality Inspector**
- No direct attributes, involved in marking/grading crops

---

## 🔗 Relationships

- A **Farmer List** entry is **assigned to** a **Logistics Partner**.
- A **Farmer List** entry **has** **Buyers** associated with it.
- **Buyers** can **buy** **Crops**.
- **Crops** are **marked by** a **Quality Inspector**.
- **Logistics Partners** can receive **Weather Warnings** and have potential **Disputes**.

---

## 📝 Notes

- This ERD represents a simplified supply chain process for agricultural produce.
- All relationships and entities are modeled for database design and implementation purposes.
