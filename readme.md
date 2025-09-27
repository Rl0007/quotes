# Collaborative Quote Wall

Welcome to the **Collaborative Quote Wall** 🎉  
This is part of the Git & GitHub workshop.  
Everyone will contribute a motivational, funny, or programming-related quote to this project.

The website will live at 👉 [https://quotes.rl0007.com](https://quotes.rl0007.com)  

---

## 🚀 How to Contribute (using GitHub Codespaces)

1. **Fork this repository**  
   - Click the `Fork` button at the top-right of this page.

2. **Open in Codespaces**  
   - On your forked repo, click the green `Code` button.  
   - Select **Codespaces → Create codespace on master**.  
   - This opens a cloud-based VS Code environment 

3. **Add your quote**  
   - Open `quotes.json` file.  
   - Copy this template into end of the file and fill it out:

     ```json
     {
       "text": "Your amazing quote goes here.",
       "author": "Quote Author",
       "contributor": "your-github-username",
       "category": "motivation | inspiration | programming"
     }
     ```

4. **Commit your changes**  
   - In Codespaces, open the **Source Control** tab (left sidebar).  
   - Enter a commit message like:  
     ```
     feat: add my quote @your-github-username
     ```  
   - Click Commit & Push.

5. **Open a Pull Request**  
   - Go to your fork on GitHub.  
   - You’ll see a banner: *“Compare & pull request”*. Click it.  
   - Create a Pull Request to merge your quote into the project. 🎉  

---

## 📝 Example Quotes

```json
{
  "text": "Code is like humor. When you have to explain it, it's bad.",
  "author": "Cory House",
  "contributor": "dev-bob",
  "category": "programming"
}
