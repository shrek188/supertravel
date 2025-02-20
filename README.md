🚀 SuperTravel is a Supabase-powered task management system that provides API-based task tracking, automated notifications, and user authentication via Magic Link. This project is open to developers contributing through Sweat Equity, where your contributions can earn you long-term equity or future token rewards.

📌 1️⃣ Project Overview
Backend: Supabase (Database, Auth, Edge Functions)
Frontend: Codev (co.dev-based Web App)
API: RESTful API with Supabase SDK
Authentication: Magic Link Login

Task Management: Supabase tasks table with automated email notifications
📌 2️⃣ How to Join? (Magic Link Login)
We use Magic Link authentication, so no password is required. Just enter your email, and you'll receive a login link.

👉 Sign in now & explore your tasks!
🔗 Magic Link Login：https://tintnbsonaskagix-5jfkqt5qd.preview.co.dev/

Steps to log in:
1️⃣ Open the above link and enter your email
2️⃣ Check your inbox for the Magic Link
3️⃣ Click the link and log in to access the developer portal

📌 3️⃣ API Access & Development
You can access and interact with the tasks data using Supabase API.

🔹 Example: Fetch Tasks via API
bash

curl -X GET "https://your-project.supabase.co/rest/v1/tasks" \
     -H "Authorization: Bearer ACCESS_TOKEN"
🔹 Example: Fetch Tasks using JavaScript SDK
javascript

import { createClient } from '@supabase/supabase-js';

const supabase = createClient(
  'https://your-project.supabase.co',
  'YOUR_SUPABASE_ANON_KEY'
);

async function getTasks(userEmail) {
  const { data, error } = await supabase
    .from('tasks')
    .select('*')
    .eq('assigned_to', userEmail);
  console.log(data, error);
}
📌 4️⃣ How to Contribute? (Contributing Guide)
We welcome developers to Fork this project and contribute through Pull Requests. 🎯

Step-by-step contribution process
1️⃣ Fork this repository
2️⃣ Clone your fork locally

bash

git clone https://github.com/your-username/supertravel.git
cd supertravel
3️⃣ Create a new feature branch

bash

git checkout -b feature-xxx
4️⃣ Make your changes & commit them

bash

git add .
git commit -m "Add new feature xxx"
git push origin feature-xxx
5️⃣ Open a Pull Request (PR) on GitHub and wait for review! ✅

📌 5️⃣ Security & Access Control
🔒 Row Level Security (RLS) is enabled – You can only access your own assigned tasks.
🔒 No service_role key exposure – Only anon key is provided.
🔒 Developers can modify tasks but have limited access to other tables.

📌 6️⃣ Stay Connected
📩 Contact Founder: meritprivateinvestor@gmail.com
🔗 Project Website: https://your-codev-app.co.dev](https://tintnbsonaskagix-5jfkqt5qd.preview.co.dev/
🎯 GitHub Repository: https://github.com/shrek188/supertravel

🚀 Join us and help build the future of SuperTravel! 😃

