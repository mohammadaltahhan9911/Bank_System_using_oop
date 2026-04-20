<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bank System Using OOP</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            line-height: 1.6;
            background-color: #f5f5f5;
        }
        h1, h2 {
            color: #2c3e50;
        }
        ul {
            margin-left: 20px;
        }
        .container {
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .section {
            margin-bottom: 25px;
        }
    </style>
</head>
<body>

<div class="container">

    <h1>🏦 Bank System Using OOP</h1>
    <p><strong>A robust, console-based banking management application built with Object-Oriented Programming principles and a unique binary permission system.</strong></p>

    <div class="section">
        <h2>📖 Overview</h2>
        <p>
            Bank System Using OOP is a comprehensive console application designed to simulate core banking operations.
            It demonstrates the practical application of Object-Oriented Programming (OOP) concepts such as Encapsulation,
            Inheritance, and Abstraction.
        </p>
        <p>
            The system is designed with security and scalability in mind, featuring a custom-built Bitwise Permission System
            to manage user access levels efficiently.
        </p>
    </div>

    <div class="section">
        <h2>✨ Key Features</h2>

        <h3>👥 Client Management</h3>
        <ul>
            <li>Add New Customer: Create new client accounts with unique IDs.</li>
            <li>Update Customer: Modify existing client details.</li>
            <li>Delete Customer: Remove client records safely from the system.</li>
            <li>View Client List: Display a formatted list of all active clients.</li>
        </ul>

        <h3>💼 User & Admin Management</h3>
        <ul>
            <li>User Management: Create and manage system users (bank staff).</li>
            <li>Granular Permissions: Assign specific roles and access rights to different users.</li>
        </ul>

        <h3>💰 Transactions</h3>
        <ul>
            <li>Deposits: Add funds to client accounts.</li>
            <li>Withdrawals: Deduct funds with balance validation.</li>
            <li>Total Balances: View total liquidity across all clients.</li>
        </ul>
    </div>

    <div class="section">
        <h2>🔐 Security Highlight: Binary Permission System</h2>
        <p>
            This project utilizes a Bitwise Permission System to handle user authorization. Instead of storing long strings
            of roles, permissions are calculated using binary flags.
        </p>

        <ul>
            <li>1 (001): Show List</li>
            <li>2 (010): Add Client</li>
            <li>4 (100): Delete Client</li>
        </ul>

        <p><strong>Example:</strong> User with value 3 (011) can Show List AND Add Client.</p>
    </div>

    <div class="section">
        <h2>🛠️ Technical Implementation</h2>
        <ul>
            <li>Language: C++</li>
            <li>OOP Principles: Classes for Clients, Users, and Transactions</li>
            <li>Data Storage: Text Files (.txt)</li>
            <li>Algorithm: Bitwise permission calculations</li>
        </ul>
    </div>

    <div class="section">
        <h2>🚀 Future Roadmap</h2>
        <ul>
            <li>Web Migration: Convert to Web API + Frontend</li>
            <li>Database Integration: Move to SQL</li>
            <li>Transaction History: Add logs for transactions</li>
            <li>Interest Calculation: Add savings account logic</li>
        </ul>
    </div>

    <div class="section">
        <h2>🙏 Acknowledgment</h2>
        <p>
            Special thanks to Dr. Mohammed Abu Hadhoud for his invaluable teaching and guidance.
            This project was inspired by Programmingadvices.com.
        </p>
    </div>

    <div class="section">
        <h2>📬 Contact</h2>
        <p>Feel free to reach out for any questions or collaboration.</p>
    </div>

</div>

</body>
</html>
