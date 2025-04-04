<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6; max-width: 800px; margin: auto; padding: 2rem;">

  <h1>🥗 Recipe Finder using Python & Streamlit</h1>

  <h2>📖 Overview</h2>
  <p>
    This project is a web-based <strong>Recipe Finder</strong> app built with <strong>Python</strong> and <strong>Streamlit</strong>.
    Users can search for recipes by entering ingredients and choosing dietary preferences. It retrieves real-time data by making API calls to the <strong>Spoonacular REST API</strong> 
    and displays recipe results in a user-friendly interface.
  </p>

  <h2>⚙️ Installation</h2>
  <ol>
    <li>
      <strong>Clone the repository</strong>:
      <pre><code>git clone https://github.com/your-username/recipe-finder.git
cd recipe-finder</code></pre>
    </li>
    <li>
      <strong>Create a virtual environment</strong> (optional but recommended):
      # Windows
      <pre><code>
python -m venv venv
venv\Scripts\activate
      </code></pre>
    </li>
    <li>
      <strong>Install dependencies</strong>:
      <pre><code>pip install -r requirements.txt</code></pre>
    </li>
    <li>
      <strong>Get an API key</strong> from <a href="https://spoonacular.com/food-api" target="_blank">Spoonacular</a> and create a <code>secrets.toml</code> file in the root directory:
      <pre><code>[api_key]
api_key = "YOUR_API_KEY_HERE"</code></pre>
    </li>
    <li>
      <strong>Run the app</strong>:
      <pre><code>streamlit run recipe_finder.py</code></pre>
    </li>
  </ol>

  <h2>🧑‍🍳 Usage</h2>
  <ul>
    <li>Enter <strong>comma-separated ingredients</strong> like <code>chicken, rice, broccoli</code>.</li>
    <li>Choose a <strong>dietary restriction</strong> from the dropdown (optional).</li>
    <li>Click <strong>"Find Recipes"</strong> to see matching results.</li>
    <li>View recipe title, prep time, servings, and full source link in a table format.</li>
  </ul>

  <h2>🛠️ Technologies Used</h2>
  <ul>
    <li>Python 3.11+</li>
    <li>Streamlit</li>
    <li>Pandas</li>
    <li>Requests</li>
    <li>Spoonacular API</li>
  </ul>

  <h2>💡 Notes</h2>
  <ul>
    <li>Tested with <code>streamlit==1.20.0</code>, <code>pandas==1.5.3</code>, and <code>requests==2.28.2</code>.</li>
    <li>No extra front-end code needed — all UI handled by Streamlit.</li>
    <li>Background image and styling are handled via custom HTML/CSS injection inside Streamlit.</li>
  </ul>

</body>
</html>
