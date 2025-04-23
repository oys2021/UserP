Recommended Workflow
Here's the typical workflow you should follow:

Checkout main branch and pull the latest changes:

bash
Copy
Edit
git checkout main
git pull origin main
Switch back to your feature branch:

bash
Copy
Edit
git checkout feature/exception-handling
Merge the updated main branch into your feature branch:

bash
Copy
Edit
git merge main
Push your feature branch (if everything is good):

bash
Copy
Edit
git push origin feature/exception-handling
