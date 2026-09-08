# GoGetCash

**Cash-in Cash-out Management And Track Money Movement**

GoGetCash is a comprehensive personal finance management Android application designed to help users track their cash flow, manage loans, and monitor financial transactions with ease. Whether you're recording daily expenses, tracking income, or managing borrowed and lent money, GoGetCash provides a clean, intuitive interface to keep your finances organized.

---

## 📱 Features

- **Dashboard Overview** – Get a quick snapshot of your total cash in, cash out, and current balance at a glance.
- **Cash-In / Cash-Out** – Easily record income and expense transactions with categories and notes.
- **Loan Management** – Add, track, and manage loans (both borrowed and lent) with detailed status updates.
- **Transaction History** – View a complete log of all your financial activities, searchable and filterable.
- **Reports** – Generate financial reports to analyze your spending and income patterns over time.
- **Profile Management** – Manage your user profile and preferences.
- **Unpaid / Paid Tracking** – Keep track of outstanding loans and mark them as paid when settled.
- **Modern UI** – Built with Material Design principles for a clean, responsive, and user-friendly experience.

---

## 🛠️ Tech Stack

- **Language:** Kotlin
- **Framework:** Android SDK
- **Architecture:** Model-View-ViewModel (MVVM) with Activities
- **Build Tool:** Gradle (Kotlin DSL)
- **Backend:** Firebase (Authentication, Firestore, or Realtime Database – inferred from `google-services.json`)
- **Minimum SDK:** Android 5.0 (Lollipop) / API 21
- **Target SDK:** Android 13+ / API 33

---

## 🚀 Getting Started

### Prerequisites

- Android Studio (Arctic Fox or newer recommended)
- JDK 11 or higher
- An Android device or emulator (API 21+)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/JMacopio/Goget-Cash.git
   ```

2. **Open the project in Android Studio:**
   - Select `Open an Existing Project` and navigate to the cloned folder.

3. **Set up Firebase (if applicable):**
   - The project includes `google-services.json`. If you're setting up your own Firebase instance, replace this file with your own from the Firebase Console.
   - Enable Authentication and Firestore/Realtime Database as needed.

4. **Build and run:**
   - Sync the project with Gradle files.
   - Connect your device or start an emulator.
   - Click `Run` (▶) to build and install the app.

---

## 📁 Project Structure

```
Goget-Cash/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/jeysi/gogetcash/
│   │   │   │   ├── AddLoanActivity.kt          # Add new loan
│   │   │   │   ├── AnyTransaction.kt           # Generic transaction model
│   │   │   │   ├── CashFlowActivity.kt         # Cash flow overview
│   │   │   │   ├── CashInActivity.kt           # Record income
│   │   │   │   ├── CashOutActivity.kt          # Record expenses
│   │   │   │   ├── DashboardActivity.kt        # Main dashboard
│   │   │   │   ├── HistoryActivity.kt          # Transaction history
│   │   │   │   ├── HistoryAdapter.kt           # RecyclerView adapter
│   │   │   │   ├── LoanDetailsActivity.kt      # Loan details view
│   │   │   │   ├── MainActivity.kt             # Entry point / splash
│   │   │   │   ├── PaidActivity.kt             # Paid loans list
│   │   │   │   ├── ProfileActivity.kt          # User profile
│   │   │   │   ├── ReportsActivity.kt          # Financial reports
│   │   │   │   ├── SignUpActivity.kt           # User registration
│   │   │   │   ├── TransactionAdapters.kt      # Transaction list adapters
│   │   │   │   ├── UnpaidActivity.kt           # Unpaid loans list
│   │   │   │   └── ui/theme/                   # Theme and styling
│   │   │   ├── res/                            # Resources (layouts, drawables, values)
│   │   │   └── AndroidManifest.xml             # App manifest
│   │   ├── androidTest/                        # Instrumentation tests
│   │   └── test/                               # Unit tests
│   ├── build.gradle.kts                        # App-level build config
│   ├── google-services.json                    # Firebase configuration
│   └── proguard-rules.pro                      # ProGuard rules
├── gradle/                                     # Gradle wrapper
├── .gitignore
├── build.gradle.kts                            # Project-level build config
├── SECURITY.md                                # Security policy
└── settings.gradle.kts                         # Project settings
```

---

## 🎮 How to Use

1. **Sign Up / Log In** – Create an account or log in to access your financial dashboard.
2. **Dashboard** – View your current balance, total cash in, and total cash out.
3. **Add Transactions** – Use the `Cash In` or `Cash Out` buttons to record income or expenses.
4. **Manage Loans** – Navigate to the loan section to add new loans, track unpaid balances, or mark loans as paid.
5. **View History** – Check your complete transaction history with timestamps and categories.
6. **Generate Reports** – Access the reports section to analyze your financial data.

---

## 🔒 Security

GoGetCash takes security seriously. If you discover a security vulnerability, please **do not** report it through public GitHub issues. Instead, email us at **`security@gogetcash.com`** with details about the vulnerability, steps to reproduce, and any relevant proof-of-concept.

For more information, see the [SECURITY.md](SECURITY.md) file.

---

## 🤝 Contributing

This is a personal project, but contributions, suggestions, and feedback are welcome! Feel free to:

- Fork the repository and submit pull requests.
- Open issues for bugs or feature requests.
- Reach out with any questions or ideas.

---

## 📄 License

All rights reserved. This project is for educational and portfolio purposes only. Please contact the author for permissions beyond personal learning.

---

## 👨‍💻 Author

**Jorge Matthew Acopio** ([JMacopio](https://github.com/JMacopio))

Built in November 2025 as a personal finance management tool to demonstrate Android development skills with Kotlin and Firebase.

---

*GoGetCash – Take control of your cash flow, one transaction at a time.*
