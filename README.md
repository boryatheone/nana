# nana
from flask import Flask, render_template

# Create a Flask web application
app = Flask(__name__)

# Define routes
@app.route('/')
def index():
    return render_template('index.html')

@app.route('/about')
def about():
    return render_template('about.html')

@app.route('/contact')
def contact():
    return render_template('contact.html')

if __name__ == '__main__':
    # Run the Flask app
    app.run(debug=True)
from flask import Flask, render_template

# Create a Flask web application
app = Flask(__name__)

# Define routes
@app.route('/')
def index():
    return render_template('index.html')

@app.route('/about')
def about():
    return render_template('about.html')

@app.route('/contact')
def contact():
    return render_template('contact.html')

if __name__ == '__main__':
    # Run the Flask app
    app.run(debug=True)
xxx
gfhdghkfjoli
