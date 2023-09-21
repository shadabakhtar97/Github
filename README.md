# Github
## Learn GitHub Deep Dive

In GitHub, you can format the content of your README.md file using Markdown, which is a lightweight markup language that allows you to style and structure your text. Markdown is widely used for creating documentation, README files, and other text-based content on GitHub and other platforms.

Here are some common Markdown formatting elements you can use in your GitHub README.md file:

1. Headers:
   Use hashtags (#) to create headers of different levels. For example:
   ```markdown
   # Header 1
   ## Header 2
   ### Header 3
   ```

2. Emphasis:
   Use asterisks (*) or underscores (_) to add emphasis to text:
   ```markdown
   *italic* or _italic_
   **bold** or __bold__
   ```

3. Lists:
   You can create ordered (numbered) and unordered (bullet) lists:
   ```markdown
   - Item 1
   - Item 2
     - Subitem 2.1
     - Subitem 2.2
   1. First item
   2. Second item
   ```

4. Links:
   You can create links using square brackets for the link text and parentheses for the URL:
   ```markdown
   [GitHub](https://github.com)
   ```

5. Images:
   You can embed images using a similar syntax to links but with an exclamation mark (!) in front:
   ```markdown
   ![Alt Text](https://example.com/image.jpg)
   ```

6. Code:
   You can format code inline with backticks (`) and create code blocks with triple backticks (```):
   Inline code: `code`
   ```python
   def example_function():
       return "Hello, World!"
   ```

7. Quotes:
   You can create block quotes using the greater-than symbol (>) at the beginning of a line:
   ```markdown
   > This is a block quote.
   ```

8. Horizontal Rules:
   You can create horizontal rules with three or more hyphens, asterisks, or underscores:
   ```markdown
   ---
   ```

9. Tables:
   You can create tables using pipes (|) and hyphens (-) for headers:
   ```markdown
   | Header 1 | Header 2 |
   |----------|----------|
   | Cell 1   | Cell 2   |
   ```

10. Task Lists:
    You can create task lists by using square brackets with a space for checkboxes:
    ```markdown
    - [x] Task 1
    - [ ] Task 2
    - [ ] Task 3
    ```

11. Escaping Characters:
    To display special characters as plain text (e.g., asterisks or square brackets), you can escape them with a backslash (\):
    ```markdown
    \* This is an escaped asterisk \*
    ```

You can combine and nest these elements to format your README.md file in a way that suits your project's documentation needs. GitHub will render the Markdown content as formatted text when you view the README file on the repository page. Make sure to preview your changes on GitHub to ensure they appear as expected.

### --------------------------------------------------------------------------------------------------------------------------------
### What is personal access token in github ?

A personal access token (PAT) in GitHub is a secure way to authenticate and interact with GitHub's APIs and services on behalf of a user or organization. It serves as an alternative to using a password for authentication and provides a more controlled and secure way to access GitHub resources programmatically. PATs are often used by developers and applications to perform various tasks like pushing code, accessing repositories, or managing GitHub actions.

Here are some key points about personal access tokens in GitHub:

1. Authentication: Instead of using your GitHub username and password to access GitHub through command-line tools, Git clients, or applications, you can use a personal access token for authentication.

2. Scopes: Personal access tokens can be scoped, which means you can specify the permissions or access levels that the token has. For example, you can create a token with read-only access to public repositories or full access to private repositories.

3. Security: Personal access tokens are more secure than using passwords because they can be revoked or regenerated at any time without changing your password. This allows you to control and manage access to your GitHub account and resources more effectively.

4. Token Lifespan: You can set an expiration date for personal access tokens to limit their validity. This adds an additional layer of security, especially for long-lived tokens.

5. Usage: PATs are typically used in command-line tools, scripts, CI/CD pipelines, and applications that need to interact with GitHub programmatically. When using a PAT, you include it in the authentication process when making API requests to GitHub.

Creating a personal access token in GitHub involves going to your GitHub account settings, navigating to the "Developer settings" or "Developer applications" section, and then generating a new token with the desired permissions and scope. It's important to keep your personal access tokens secure and not share them publicly, as they can be used to access and modify your GitHub resources.

Remember to follow GitHub's best practices for token management and rotate tokens regularly for enhanced security.
