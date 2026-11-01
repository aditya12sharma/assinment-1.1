Explanatory Paragraph
When a user types a URL (Uniform Resource Locator) into a web browser such as Google Chrome, the browser first identifies the website's domain name and finds its IP address using DNS (Domain Name System). The browser then sends an HTTP (Hypertext Transfer Protocol) or HTTPS (Hypertext Transfer Protocol Secure) request to the web server, which is a computer that stores and delivers website content. HTTPS is the secure version of HTTP that encrypts data exchanged between the browser and server. The server processes the request and, if required, retrieves information from a database, which stores and manages website data. The server then sends an HTTP response containing the requested information, such as HTML, CSS, JavaScript, and images, back to the browser. The browser interprets these files and displays the website on the screen. This process is called the request-response cycle. A static website displays fixed content that remains the same for every user unless its files are changed, whereas a dynamic website generates or updates content based on user input, database information, or other conditions.
2. Difference Between Static and Dynamic Websites
Static Website	Dynamic Website
Displays fixed content.	Displays content that can change.
Usually uses HTML and CSS.	Uses server-side programming and may use a database.
Content is generally the same for every visitor.	Content may differ for different users.
Example: A basic portfolio website.	Example: Amazon or Facebook.

3. Practical Task: Inspect Network Requests
Follow these steps to inspect website requests using Google Chrome:
1. Open Google Chrome and visit any website, such as https://www.wikipedia.org.
2. Right-click anywhere on the page and select Inspect.
3. Open the Network tab in Chrome DevTools.
4. Refresh the website while the Network tab is open.
5. Observe the requests and responses appearing in the Network panel.
6. Click on any request to view its details, such as Headers, Preview, Response, and Timing.
7. Take a screenshot of the Network tab showing the requests