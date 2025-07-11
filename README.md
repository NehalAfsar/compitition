#Creator Analytics Dashboard

This project is a web-based Creator Analytics Dashboard designed to help content creators monitor their performance across various metrics, manage content, track earnings, understand their audience, and configure settings.

Features
The dashboard includes the following key sections:

Login Page (index.html): A simple login interface for users to access the dashboard.

Dashboard Overview (dashboard.html): Provides a quick snapshot of key performance indicators like active users, questions answered, session length, knowledge gain, views over time, and earnings overview. It also features a real-time live views counter.

Content Management (content.html): Allows creators to view and manage their content with filtering options by type (videos, shorts, live), visibility (public, private, unlisted), monetization status, and date range. It includes a search bar and pagination for easy navigation.

Earnings Report (earning.html): Offers a detailed breakdown of revenue, total views, average session length, pending earnings, and growth metrics. It includes a customizable revenue trend graph and a list of content earnings.

Audience Analytics (Audience.html): Helps creators understand their audience demographics, engagement, and growth. It features charts for audience growth, gender distribution, age distribution, and a list of top-performing content.

Settings (setting.html): Enables users to manage their profile, account settings (email, password), notification preferences, and theme (light/dark mode).

Technologies Used
The project is built using standard web technologies:

HTML5: For the basic structure of the web pages.

CSS3: For styling, including responsive design and custom themes (light/dark mode) using CSS variables. Some pages also leverage Tailwind CSS via CDN.

JavaScript: For dynamic content, interactive elements, chart rendering (using Chart.js), theme toggling, sidebar functionality, and data filtering/pagination.

Chart.js: A popular JavaScript library for creating interactive charts and graphs.

Font Awesome: For various icons used throughout the dashboard.

Setup and Usage
To run this project locally, follow these steps:

Clone the repository (if applicable, or download the provided files).

Navigate to the project directory in your file system.

Open the index.html file in your web browser. This is the login page.

Enter any email and an 8-character password to log in. The login is a simple client-side redirection for demonstration purposes and does not involve server-side authentication.

After logging in, you will be redirected to the dashboard.html page.

Navigate through different sections of the dashboard using the sidebar links.

Experiment with theme toggling (moon/sun icon) to switch between light and dark modes.

In the Content section, try out the search, content type tabs, visibility filters, and monetization filters. Use the pagination controls to navigate through content.

File Structure
The project has the following file structure:

.
├── index.html                # Login Page

├── dashboard.html            # Main Dashboard Page

├── content.html              # Content Management Page

├── earning.html              # Earnings Report Page

├── Audience.html             # Audience Analytics Page

├── setting.html              # Settings Page

├── css/

│   ├── Audience_style.css    # Styles for Audience and shared components

│   ├── Earning2_style.css    # Styles for Earnings page

│   └── settings.css          # Styles for Settings page

└── javascript/

    ├── Audience_script.js    # JavaScript for Audience page functionalities
    
    ├── content_script.js     # JavaScript for Content page functionalities (currently inlined in content.html)
    
    └── Earning2_script.js    # JavaScript for Earnings page functionalities
    

(Note: Some JavaScript code might be inlined directly within the HTML files for simplicity in this version.)

Customization
Styling: Modify the CSS files (Audience_style.css, Earning2_style.css, settings.css) to change the look and feel of the dashboard. CSS variables are extensively used for easy theme customization.

Data: The current data is mock data generated by JavaScript. To integrate with a real backend, you would replace the mock data generation with API calls to fetch actual analytics.

Charts: Adjust chart types, data, and options in the JavaScript files (e.g., Audience_script.js, dashboard.html script, Earning2_script.js) to display different visualizations or data.

Contributing
Contributions are welcome! If you find any bugs or have suggestions for improvements, please feel free to open an issue or submit a pull request.

License
This project is open-source and available under the MIT License.
