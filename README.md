# TaqdeerNetwork.com
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HR Dashboard - Home</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .active {
            background-color: #3b82f6;
            color: white;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body class="bg-gray-50">
    <div class="flex flex-col min-h-screen">
        <!-- Header -->
        <header class="bg-blue-600 text-white shadow-lg">
            <div class="container mx-auto px-4 py-4 flex justify-between items-center">
                <div class="flex items-center space-x-2">
                    <img src="logo.jpg"="https://place.c/50x50" alt="Company logo with modern blue and white design showing stylized human figures" class="rounded-full">
                    <h1 class="text-2xl font-bold">HR Dashboard</h1>
                </div>
                <nav>
                    <ul class="flex space-x-6">
                        <li><a href="home.html" class="px-3 py-2 rounded active">Home</a></li>
                        <li><a href="employee.html" class="px-3 py-2 rounded hover:bg-blue-500">Employees</a></li>
                        <li><a href="salary.html" class="px-3 py-2 rounded hover:bg-blue-500">Salary</a></li>
                        <li><a href="attandance.html" class="px-3 py-2 rounded hover:bg-blue-500">Attandance</a></li>
                        <li><a href="New hire.html" class="px-3 py-2 rounded hover:bg-blue-500">New Hire</a></li>
                    </ul>
                </nav>
            </div>
        </header>
        <!-- Main Content -->
        <main class="flex-grow container mx-auto px-4 py-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Welcome to HR Dashboard</h2>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto">Streamline your HR processes with our comprehensive dashboard solution</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Employee management Card -->
               <a href="employee management.html" class="card bg-white rounded-lg shadow-md overflow-hidden transition duration-300">
                    <div class="p-6">
                        <div class="flex justify-center mb-4">
                            <div class="bg-red-100 p-3 rounded-full">
                                <img src="https://placehold.co/50x50" alt="Icon representing employee all data and record  with document and exit door symbol" class="w-50 h-50">
                            </div>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-1500 mb-2">Employee management</h3>
                        <p class="text-gray-3000">View and manage employee data and record</p>
                    </div>
                   </a>
                <!-- Salary Card -->
                <a href="salary.html" class="card bg-white rounded-lg shadow-md overflow-hidden transition duration-300">
                    <div class="p-6">
                        <div class="flex justify-center mb-4">
                            <div class="bg-green-100 p-3 rounded-full">
                                <img src="https://placehold.co/50x50" alt="Icon representing financial documents with dollar sign symbol" class="w-12 h-12">
                            </div>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Salary</h3>
                        <p class="text-gray-600">Generate and manage employee payroll records</p>
                    </div>
                </a>
                <!-- Attendance Card -->
                <a href="Attandance.html" class="card bg-white rounded-lg shadow-md overflow-hidden transition duration-300">
                    <div class="p-6">
                        <div class="flex justify-center mb-4">
                            <div class="bg-yellow-100 p-3 rounded-full">
                                <img src="https://placehold.co/50x50" alt="Icon representing attendance clock with check-in/check-out symbols" class="w-12 h-12">
                            </div>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Attandance</h3>
                        <p class="text-gray-600">Track employee attendance and working hours</p>
                    </div>
                </a>
                <!-- Leave Card -->
                <a href="leave.html" class="card bg-white rounded-lg shadow-md overflow-hidden transition duration-300">
                    <div class="p-6">
                        <div class="flex justify-center mb-4">
                            <div class="bg-purple-100 p-3 rounded-full">
                                <img src="https://placehold.co/50x50" alt="Icon representing vacation time with beach umbrella and palm tree" class="w-12 h-12">
                            </div>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Leave Tracker</h3>
                        <p class="text-gray-600">Manage employee leave requests and approvals</p>
                    </div>
                </a>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mt-8">
                <!-- Terminate Employee List Card -->
                <a href="resignations.html" class="card bg-white rounded-lg shadow-md overflow-hidden transition duration-300">
                    <div class="p-6">
                        <div class="flex justify-center mb-4">
                            <div class="bg-red-100 p-3 rounded-full">
                                <img src="https://placehold.co/50x50" alt="Icon representing employee Termination with document and exit door symbol" class="w-12 h-12">
                            </div>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Termination Latter</h3>
                        <p class="text-gray-600">View and manage employee Termination</p>
                    </div>
                </a>

                <!-- Reports Card -->
                <a href="reports.html" class="card bg-white rounded-lg shadow-md overflow-hidden transition duration-300">
                    <div class="p-6">
                        <div class="flex justify-center mb-4">
                            <div class="bg-indigo-100 p-3 rounded-full">
                                <img src="https://placehold.co/50x50" alt="Icon representing analytics reports with bar chart and pie chart symbols" class="w-12 h-12">
                            </div>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Reports</h3>
                        <p class="text-gray-600">Generate HR analytics and reports</p>
                    </div>
                </a>

                <!-- Contact Card -->
                <a href="contacts.html" class="card bg-white rounded-lg shadow-md overflow-hidden transition duration-300">
                    <div class="p-6">
                        <div class="flex justify-center mb-4">
                            <div class="bg-pink-100 p-3 rounded-full">
                                <img src="https://placehold.co/50x50" alt="Icon representing contact information with phone and email symbols" class="w-12 h-12">
                            </div>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Contacts</h3>
                        <p class="text-gray-600">Contact information and support</p>
                    </div>
                </a>
            </div>
        </main>

        <!-- Footer -->
        <footer class="bg-gray-800 text-white py-8">
            <div class="container mx-auto px-4">
                <div class="flex flex-col md:flex-row justify-between items-center">
                    <div class="mb-4 md:mb-0">
                        <h3 class="text-xl font-bold mb-2">HR Dashboard</h3>
                        <p class="text-gray-400">© 2023 Company Name. All rights reserved.</p>
                    </div>
                    <nav>
                        <ul class="flex space-x-6">
                            <li><a href="index.html" class="hover:text-blue-400">Home</a></li>
                            <li><a href="privacy.html" class="hover:text-blue-400">Privacy Policy</a></li>
                            <li><a href="terms.html" class="hover:text-blue-400">Terms</a></li>
                            <li><a href="contact.html" class="hover:text-blue-400">Contact</a></li>
                        </ul>
                    </nav>
                </div>
            </div>
        </footer>
    </div>
</body>
</html>
```
