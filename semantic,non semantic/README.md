Documentation on Semantic and Non-Semantic HTML Elements

Semantic HTML Elements
Semantic HTML elements clearly describe their meaning in a way that is both human- and machine-readable. These elements provide better structure and readability for both developers and search engines, enhancing accessibility and SEO.

List of Semantic HTML Elements:

<article>: Represents a self-contained piece of content which could be independently distributed or reused.

html
Copy code
<article>
    <h2>Article Title</h2>
    <p>This is an example of an article.</p>
</article>
<aside>: Represents content indirectly related to the main content, like a sidebar.

html
Copy code
<aside>
    <h2>Related Links</h2>
    <p>Links to related content.</p>
</aside>
<details>: Represents a disclosure widget from which the user can obtain additional information.

html
Copy code
<details>
    <summary>More Info</summary>
    <p>This is additional information.</p>
</details>
<figcaption>: Represents a caption or legend for a figure.

html
Copy code
<figure>
    <img src="image.jpg" alt="Description">
    <figcaption>Caption for the image.</figcaption>
</figure>
<figure>: Represents self-contained content, such as illustrations, diagrams, photos, code listings, etc.

html
Copy code
<figure>
    <img src="image.jpg" alt="Description">
    <figcaption>Caption for the image.</figcaption>
</figure>
<footer>: Represents the footer for a section or document.

html
Copy code
<footer>
    <p>&copy; 2024 My Website</p>
</footer>
<header>: Represents introductory content, typically a group of introductory or navigational aids.

html
Copy code
<header>
    <h1>Website Title</h1>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>
<main>: Represents the dominant content of the <body>.

html
Copy code
<main>
    <article>
        <h2>Main Article</h2>
        <p>This is the main content of the page.</p>
    </article>
</main>
<mark>: Represents text highlighted for reference or notation purposes.

html
Copy code
<p>This is <mark>highlighted</mark> text.</p>
<nav>: Represents a section with navigation links.

html
Copy code
<nav>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>
<section>: Represents a generic section of a document or application.

html
Copy code
<section>
    <h2>Section Title</h2>
    <p>This is an example of a section.</p>
</section>
<summary>: Represents a summary or caption for the <details> element.

html
Copy code
<details>
    <summary>More Info</summary>
    <p>This is additional information.</p>
</details>
<time>: Represents a specific period in time.

html
Copy code
<time datetime="2024-07-27">July 27, 2024</time>
Non-Semantic HTML Elements
Non-semantic HTML elements do not describe their meaning. They are used as generic containers for content and are often used for styling purposes.

List of Non-Semantic HTML Elements:

<div>: A generic container for flow content. It has no specific meaning.

html
Copy code
<div>
    This is a div element.
</div>
<span>: A generic inline container for phrasing content. It has no specific meaning.

html
Copy code
<p>This is a <span>span element</span> inside a paragraph.</p>
Comparison with Examples
Semantic HTML Example:

html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Semantic HTML Example</title>
</head>
<body>
    <header>
        <h1>My Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <article>
            <h2>Article Title</h2>
            <p>This is an example of an article.</p>
        </article>
        <section>
            <h2>Section Title</h2>
            <p>This is an example of a section.</p>
        </section>
    </main>
    <aside>
        <h2>Related Links</h2>
        <p>Links to related content.</p>
    </aside>
    <footer>
        <p>&copy; 2024 My Website</p>
    </footer>
</body>
</html>
Non-Semantic HTML Example:

html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Non-Semantic HTML Example</title>
</head>
<body>
    <div id="header">
        <h1>My Website</h1>
        <div id="nav">
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </div>
    <div id="content">
        <div class="article">
            <h2>Article Title</h2>
            <p>This is an example of an article.</p>
        </div>
        <div class="section">
            <h2>Section Title</h2>
            <p>This is an example of a section.</p>
        </div>
    </div>
    <div id="aside">
        <h2>Related Links</h2>
        <p>Links to related content.</p>
    </div>
    <div id="footer">
        <p>&copy; 2024 My Website</p>
    </div>
</body>
</html>
Conclusion
Using semantic HTML elements improves the accessibility, readability, and SEO of a webpage. While non-semantic elements are still useful for styling and layout purposes, semantic elements should be preferred for structuring content as they provide more meaningful information to browsers, search engines, and assistive technologies.