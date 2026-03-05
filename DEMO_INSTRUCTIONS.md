# Meta Forex Platform - Demo Instructions

## 🚀 Quick Start Guide

### Step 1: Access the Platform
1. Open the `index.html` file in your web browser
2. You will see the login/cover page

### Step 2: Login
The platform comes with pre-filled demo credentials:

**Administrator Access:**
- Email: `adeganglobal@gmail.com`
- Password: `admin123`
- Click "Login to Dashboard" to access Admin Dashboard

**User Access:**
- Enter any email and password
- Click "Login to Dashboard" to access User Dashboard

## 📋 Platform Navigation

### Admin Dashboard (`admin-dashboard.html`)
Access all administrative features:
- User Management (Create, Edit, Activate, Deactivate, Delete)
- Balance Management (Credit/Debit user accounts)
- Wallet Balances (Real, Profit, Credit)
- Robot Trading Control
- Recent Deposits & Withdrawals
- Platform Statistics

### Trading Terminal (`trading-terminal.html`)
Professional trading interface:
- Live price charts for EUR/USD, GBP/USD, USD/JPY, BTC/USD
- Manual trading with Buy/Sell buttons
- Robot Trading configuration
- Active trades monitoring
- Trade history

### Deposit Page (`deposit.html`)
Fund your account:
- Multiple payment methods (Bank, Crypto, Gateways, Mobile Money)
- Deposit bonuses
- Payment instructions
- Transaction history

### Withdrawal Page (`withdrawal.html`)
Withdraw your funds:
- Select balance type (Real, Profit, Credit)
- Multiple withdrawal methods
- Fee calculation (no fees over $500)
- Transaction history

### User Dashboard (`user-dashboard.html`)
Personal trading space:
- Performance statistics
- Profile management
- KYC verification status
- Support ticket system

## 🤖 Robot Trading Demo

### How to Use Robot Trading:
1. Go to Trading Terminal
2. Scroll to "Robot Trading" section
3. Configure settings:
   - Auto Buy/Sell: Set to "Yes"
   - Pull Duration: 6 seconds (default)
   - Profit Transfer: 2 seconds (default)
   - Max Trade Amount: Enter desired amount
   - Target Wallet: Choose "Profit Balance" for withdrawable profits
4. Click "Start Robot"
5. Watch the robot analyze market and execute trades
6. Profits are automatically transferred to your target wallet

### Robot Features:
- Analyzes price movements for pull/fall patterns
- Executes unlimited buy/sell orders
- Takes profits every 2 seconds
- All profits go to withdrawable balance
- Can be stopped anytime

## 💰 Balance System Demo

### Three Balance Types:
1. **Real Balance**: Your primary trading funds
2. **Profit Balance**: Withdrawable profits (all profit can be withdrawn)
3. **Credit Balance**: Bonus credits (all credit can be withdrawn)

### How to Test:
1. Use Admin Dashboard to credit your account
2. Go to Trading Terminal to trade
3. Check balances updating in real-time
4. Withdraw from Profit or Credit balance

## 🏦 Payment Methods Demo

### Supported Methods:
**Banks:**
- International Bank Transfer
- Nigerian Banks (FCMB, Zenith, UBA)
- UK Banks

**Payment Gateways:**
- PayPal
- Stripe
- Flutterwave
- Paystack

**Cryptocurrency:**
- Bitcoin (BTC)
- Ethereum (ETH)
- Tether (USDT)

**Mobile Money:**
- OPay
- PalmPay

### Testing Deposits:
1. Go to Deposit page
2. Select any payment method
3. Enter amount (minimum $10)
4. See payment details and bonus calculation
5. Click "Proceed to Payment"

### Testing Withdrawals:
1. Go to Withdrawal page
2. Select balance type
3. Choose withdrawal method
4. Enter amount
5. See fee calculation (2% under $500, free over $500)

## 👤 User Management Demo (Admin Only)

### Create New User:
1. Go to Admin Dashboard
2. Click "+ Add New User"
3. Fill in user details
4. Set initial balance
5. Click "Create User"

### Edit User:
1. Find user in the table
2. Click "Edit" button
3. Modify balances, status, or profile
4. Click "Save Changes"

### Credit/Debit Balance:
1. Go to Balance Management section
2. Select user
3. Enter amount and reason
4. Click "Credit" or "Debit"

### Activate/Deactivate:
1. Find user in table
2. Click "Activate" or "Deactivate"
3. User status changes immediately

### Delete User:
1. Find user in table
2. Click "Delete" button
3. Confirm deletion

## 📊 Trading Demo

### Manual Trading:
1. Select a currency pair (EUR/USD, GBP/USD, etc.)
2. Set trade amount
3. Choose leverage (1:1 to 1:100)
4. Set optional Stop Loss and Take Profit
5. Click "BUY" (for price going up) or "SELL" (for price going down)
6. Watch trade in "Active Trades" section
7. Close trade manually or wait for SL/TP

### Price Simulation:
- Prices update automatically every second
- Charts show real-time price movements
- Colors indicate direction (green = up, red = down)

## 🔐 Security Features Demo

### Profile Management:
1. Go to User Dashboard
2. Edit personal information
3. Update contact details
4. Change password

### KYC Verification:
- Status displayed in User Dashboard
- Shows verification progress
- Verified users have full access

### Two-Factor Authentication:
- Can be enabled/disabled in settings
- Enhances account security

## 📱 Responsive Design Demo

### Test on Different Devices:
- Desktop: Full-featured dashboard
- Tablet: Adapted layout
- Mobile: Optimized interface

### Resize Browser:
- Watch layout adapt
- Sidebar becomes collapsible
- Grids adjust automatically

## 🎨 Design Features

### Visual Elements:
- Modern dark theme with gradients
- Animated price indicators
- Interactive charts
- Smooth transitions
- Professional color scheme

### Color Coding:
- Green: Profit, success, active
- Red: Loss, error, danger
- Blue: Primary actions
- Yellow: Warning, credit

## 📈 Statistics Demo

### Platform Statistics (Admin):
- Total users count
- Active users count
- Total platform balance
- Platform profit
- Real-time updates

### User Statistics:
- Total trades
- Win rate
- Total profit
- Robot trades today

## 💡 Tips for Demo

1. **Start with Admin Dashboard** - Create users and credit accounts
2. **Test Trading Terminal** - Try manual and robot trading
3. **Check Payment Pages** - Explore deposit and withdrawal options
4. **Monitor Balances** - Watch balances update in real-time
5. **Test User Dashboard** - Explore personal features
6. **Try Different Scenarios** - Activate/deactivate users, credit/debit balances

## 🔧 Troubleshooting

### Issues:
- **Charts not loading**: Ensure Chart.js CDN is accessible
- **Prices not updating**: Check JavaScript console for errors
- **Login not working**: Verify credentials

### Browser Compatibility:
Works best on:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 📞 Support Information

**Platform Administrator:**
- Name: Olawale Abdul-Ganiyu Adeshina
- Email: adeganglobal@gmail.com
- Phone: +2349030277275

**Payment Signature:**
Olawale Abdul Gain Forex Trading

## 🎯 Demo Checklist

- [ ] Login as Administrator
- [ ] Create a new user
- [ ] Credit user balance
- [ ] Login as User
- [ ] View dashboard statistics
- [ ] Open trading terminal
- [ ] Execute manual trade
- [ ] Start robot trading
- [ ] Make a deposit
- [ ] Request a withdrawal
- [ ] Edit user profile
- [ ] Check transaction history
- [ ] Test payment methods
- [ ] Monitor balance updates
- [ ] Stop robot trading
- [ ] Close active trades
- [ ] Logout

---

**Enjoy exploring the Meta Forex Trading Platform!**

This is a comprehensive demonstration of a professional trading platform with advanced features including automated trading, multiple payment methods, and full administrative controls.