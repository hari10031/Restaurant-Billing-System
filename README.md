# 🍛 Hyderabadi Dastarkhwan - Restaurant Billing System

Welcome to **Hyderabadi Dastarkhwan**, an authentic Hyderabadi restaurant billing system! This Python-based application provides a complete point-of-sale solution for managing orders, calculating bills with GST, and maintaining customer records. Perfect for Indian restaurants serving traditional Hyderabadi cuisine.



---

## ✨ Features

### 🍽️ Comprehensive Menu System
- **65+ authentic Hyderabadi dishes** organized by category
- Scrollable menu interface for easy navigation
- Real-time price display in Indian Rupees (₹)

### 📋 Menu Categories
| Category | Highlights |
|----------|------------|
| **Biryani Specialties** | Hyderabadi Dum Biryani (Chicken, Mutton, Veg), Keema, Prawn, Fish Biryani |
| **Kebabs & Starters** | Sheek Kebab, Chicken 65, Apollo Fish, Pathar Ka Gosht, Lukhmi |
| **Curries & Gravies** | Nahari, Paya, Dalcha, Bagara Baingan, Mirchi Ka Salan |
| **Breads** | Tandoori Roti, Naan varieties, Sheermal, Rumali Roti |
| **Rice & Sides** | Bagara Rice, Jeera Rice, Raita, Salads |
| **Beverages** | Irani Chai, Sulaimani, Qahwa, Lassi, Rooh Afza |
| **Desserts** | Double Ka Meetha, Qubani Ka Meetha, Shahi Tukda, Phirni |

### 🛒 Order Management
- Add/remove items with single click or double-click
- Specify quantities for each item
- Real-time order summary updates
- Clear order functionality

### 💰 Billing & Taxes
- Automatic calculation of subtotal
- **GST Compliant**: SGST (2.5%) + CGST (2.5%) calculation
- Percentage-based discount support
- Final total with tax breakdown

### 🧾 Professional Bill Generation
- Detailed itemized receipts
- Customer information capture (Name & Phone)
- Restaurant branding and contact details
- Timestamp for each transaction

### 📊 Order History
- Persistent storage in JSON format
- View all past orders
- Double-click to view full order details
- Track customer preferences and sales

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Python 3.x** | Core programming language |
| **Tkinter** | Graphical User Interface |
| **JSON** | Order history storage |
| **datetime** | Transaction timestamps |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.x installed on your system
- Tkinter (usually comes with Python)

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/hari10031/Restaurant-Billing-System.git
   ```

### 2. Navigate to the Project Directory
   ```bash
   cd Restaurant-Billing-System
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**
   ```bash
   python "fbs copy.py"
   ```

---

## 📖 How to Use

1. **🚀 Launch** - Run the application to open the billing interface
2. **📜 Browse Menu** - Scroll through the categorized menu items
3. **➕ Add Items** - Double-click or select and click "Add Item" to add to order
4. **🔢 Set Quantity** - Enter the quantity when prompted
5. **🏷️ Apply Discount** - Use "Apply Discount" for percentage discounts
6. **💵 Calculate** - Click "Calculate Total" to see the amount
7. **🧾 Generate Bill** - Enter customer details and generate the final bill
8. **📜 View History** - Check "Order History" for past transactions

---

## 📁 Project Structure

```
Restaurant Billing System/
├── fbs copy.py          # Main application file
├── order_history.json   # Order history database
├── requirements.txt     # Python dependencies
└── README.md            # Documentation
```

---

## 🎨 Screenshots

### Main Interface
- **Header**: Maroon theme with gold text representing royal Hyderabadi heritage
- **Menu Panel**: Scrollable list with 65+ items
- **Order Summary**: Real-time order tracking
- **Action Buttons**: Add, Remove, Discount, Clear, Generate Bill, History

---



