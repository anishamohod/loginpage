<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SimpleAuth System</title>
    <style>
        :root {
            --primary-color: #4f46e5;
            --primary-hover: #4338ca;
            --danger-color: #ef4444;
            --danger-hover: #dc2626;
            --success-bg: #dcfce7;
            --success-text: #166534;
            --error-bg: #fee2e2;
            --error-text: #991b1b;
            --text-main: #1f2937;
            --text-muted: #6b7280;
            --bg-body: #f3f4f6;
            --bg-card: #ffffff;
            --border-color: #e5e7eb;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .container {
            width: 100%;
            max-width: 420px;
            perspective: 1000px;
        }

        .card {
            background: var(--bg-card);
            border-radius: 16px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
            padding: 2rem;
            width: 100%;
            animation: fadeIn 0.4s ease-out forwards;
        }

        .hidden {
            display: none !important;
        }

        /* Tabs */
        .tabs {
            display: flex;
            margin-bottom: 2rem;
            border-bottom: 2px solid var(--border-color);
        }

        .tab-btn {
            flex: 1;
            padding: 0.75rem;
            background: none;
            border: none;
            font-size: 1rem;
            font-weight: 600;
            color: var(--text-muted);
            cursor: pointer;
            position: relative;
            transition: color 0.3s ease;
        }

        .tab-btn:hover {
            color: var(--primary-color);
        }

        .tab-btn.active {
            color: var(--primary-color);
        }

        .tab-btn.active::after {
            content: '';
            position: absolute;
            bottom: -2px;
            left: 0;
            width: 100%;
            height: 2px;
            background-color: var(--primary-color);
            border-radius: 2px 2px 0 0;
            animation: slideIn 0.3s ease;
        }

        /* Forms */
        h2 {
            color: var(--text-main);
            margin-bottom: 1.5rem;
            font-size: 1.5rem;
            text-align: center;
        }

        .form-group {
            margin-bottom: 1.25rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            color: var(--text-main);
            font-size: 0.875rem;
            font-weight: 500;
        }

        .form-group input {
            width: 100%;
            padding: 0.75rem 1rem;
            border: 1px solid var(--border-color);
            border-radius: 8px;
            font-size: 1rem;
            transition: all 0.3s ease;
            outline: none;
        }

        .form-group input:focus {
            border-color: var(--primary-color);
            box-shadow: 0 0 0 3px rgba(79, 70, 229, 0.1);
        }

        /* Buttons */
        .btn {
            width: 100%;
            padding: 0.875rem;
            border: none;
            border-radius: 8px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .btn-primary {
            background-color: var(--primary-color);
            color: white;
        }

        .btn-primary:hover {
            background-color: var(--primary-hover);
            transform: translateY(-1px);
            box-shadow: 0 4px 12px rgba(79, 70, 229, 0.2);
        }

        .btn-danger {
            background-color: var(--danger-color);
            color: white;
            margin-top: 2rem;
        }

        .btn-danger:hover {
            background-color: var(--danger-hover);
            transform: translateY(-1px);
        }

        /* Messages */
        .message {
            padding: 0.75rem 1rem;
            border-radius: 8px;
            margin-bottom: 1.5rem;
            font-size: 0.875rem;
            font-weight: 500;
            text-align: center;
            animation: fadeInDown 0.3s ease;
        }

        .message.success {
            background-color: var(--success-bg);
            color: var(--success-text);
            border: 1px solid #bbf7d0;
        }

        .message.error {
            background-color: var(--error-bg);
            color: var(--error-text);
            border: 1px solid #fecaca;
        }

        /* Dashboard specific */
        .dashboard-content {
            text-align: center;
        }
        
        .dashboard-content p {
            color: var(--text-muted);
            margin-bottom: 1rem;
            line-height: 1.5;
        }

        .dashboard-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
            display: block;
        }

        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes fadeInDown {
            from { opacity: 0; transform: translateY(-10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes slideIn {
            from { transform: scaleX(0); }
            to { transform: scaleX(1); }
        }

        .fade-in {
            animation: fadeIn 0.4s ease forwards;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Auth View -->
        <div id="auth-box" class="card">
            <div class="tabs">
                <button id="tab-login" class="tab-btn active" onclick="switchTab('login')">Login</button>
                <button id="tab-register" class="tab-btn" onclick="switchTab('register')">Register</button>
            </div>

            <div id="message-box" class="message hidden"></div>

            <!-- Login Form -->
            <form id="login-form" class="fade-in">
                <h2>Welcome Back</h2>
                <div class="form-group">
                    <label for="login-email">Email Address</label>
                    <input type="email" id="login-email" required placeholder="Enter your email">
                </div>
                <div class="form-group">
                    <label for="login-password">Password</label>
                    <input type="password" id="login-password" required placeholder="Enter your password">
                </div>
                <button type="submit" class="btn btn-primary">Login</button>
            </form>

            <!-- Register Form -->
            <form id="register-form" class="hidden fade-in">
                <h2>Create Account</h2>
                <div class="form-group">
                    <label for="reg-name">Full Name</label>
                    <input type="text" id="reg-name" required placeholder="John Doe">
                </div>
                <div class="form-group">
                    <label for="reg-email">Email Address</label>
                    <input type="email" id="reg-email" required placeholder="john@example.com">
                </div>
                <div class="form-group">
                    <label for="reg-password">Password</label>
                    <input type="password" id="reg-password" minlength="6" required placeholder="Minimum 6 characters">
                </div>
                <button type="submit" class="btn btn-primary">Register</button>
            </form>
        </div>

        <!-- Dashboard View -->
        <div id="dashboard-box" class="card hidden">
            <div class="dashboard-content fade-in">
                <span class="dashboard-icon">👋</span>
                <h2>Dashboard</h2>
                <p>Welcome, <strong id="user-name-display">User</strong>!</p>
                <p>You have successfully logged into the SimpleAuth secure area.</p>
                <button id="logout-btn" class="btn btn-danger">Logout</button>
            </div>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // DOM Elements
            const authBox = document.getElementById('auth-box');
            const dashboardBox = document.getElementById('dashboard-box');
            const loginForm = document.getElementById('login-form');
            const registerForm = document.getElementById('register-form');
            const tabLogin = document.getElementById('tab-login');
            const tabRegister = document.getElementById('tab-register');
            const messageBox = document.getElementById('message-box');
            const userNameDisplay = document.getElementById('user-name-display');
            const logoutBtn = document.getElementById('logout-btn');

            let messageTimeout;

            // Tab Switching Logic
            window.switchTab = (tab) => {
                hideMessage();
                if (tab === 'login') {
                    loginForm.classList.remove('hidden');
                    registerForm.classList.add('hidden');
                    tabLogin.classList.add('active');
                    tabRegister.classList.remove('active');
                } else {
                    loginForm.classList.add('hidden');
                    registerForm.classList.remove('hidden');
                    tabLogin.classList.remove('active');
                    tabRegister.classList.add('active');
                }
            };

            // Message Handling
            function showMessage(msg, type) {
                clearTimeout(messageTimeout);
                messageBox.textContent = msg;
                messageBox.className = `message ${type}`;
                
                messageTimeout = setTimeout(() => {
                    hideMessage();
                }, 4000);
            }

            function hideMessage() {
                messageBox.className = 'message hidden';
            }

            // Session Management
            function checkSession() {
                const session = localStorage.getItem('simpleAuthSession');
                if (session) {
                    const user = JSON.parse(session);
                    userNameDisplay.textContent = user.name;
                    authBox.classList.add('hidden');
                    dashboardBox.classList.remove('hidden');
                } else {
                    authBox.classList.remove('hidden');
                    dashboardBox.classList.add('hidden');
                    switchTab('login');
                }
            }

            // Initialize app - MOVED HERE to fix ReferenceError
            checkSession();

            // Registration Logic
            registerForm.addEventListener('submit', (e) => {
                e.preventDefault();
                
                const name = document.getElementById('reg-name').value.trim();
                const email = document.getElementById('reg-email').value.trim();
                const password = document.getElementById('reg-password').value;

                if (password.length < 6) {
                    return showMessage('Password must be at least 6 characters long.', 'error');
                }

                let users = JSON.parse(localStorage.getItem('simpleAuthUsers')) || [];
                
                const userExists = users.some(u => u.email.toLowerCase() === email.toLowerCase());
                if (userExists) {
                    return showMessage('This email is already registered.', 'error');
                }

                users.push({ name, email, password });
                localStorage.setItem('simpleAuthUsers', JSON.stringify(users));
                
                registerForm.reset();
                showMessage('Registration successful! Please log in.', 'success');
                switchTab('login');
            });

            // Login Logic
            loginForm.addEventListener('submit', (e) => {
                e.preventDefault();
                
                const email = document.getElementById('login-email').value.trim();
                const password = document.getElementById('login-password').value;

                let users = JSON.parse(localStorage.getItem('simpleAuthUsers')) || [];
                
                const user = users.find(u => u.email.toLowerCase() === email.toLowerCase() && u.password === password);

                if (user) {
                    localStorage.setItem('simpleAuthSession', JSON.stringify({ name: user.name, email: user.email }));
                    loginForm.reset();
                    checkSession();
                } else {
                    showMessage('Invalid email or password.', 'error');
                }
            });

            // Logout Logic
            logoutBtn.addEventListener('click', () => {
                localStorage.removeItem('simpleAuthSession');
                checkSession();
            });
        });
    </script>
</body>
</html>