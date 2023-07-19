<div class="markdown prose w-full break-words dark:prose-invert light">
    <h1>Web Scraper for List Retrieval using Python</h1>
    <p><img src="https://img.shields.io/badge/Python-3.9%2B-blue" alt="Python">
        <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
    </p>
    <p>Welcome to our Web Scraper project! This Python-based web scraper is the result of the final project for the
        "Xpath and Web Scraping" course at Platzi. The main goal of this project is to provide a tool that allows you to
        practice web scraping and obtain a local file containing data from various web pages.</p>
    <h2>Table of Contents</h2>
    <ul>
        <li><a href="#introduction" target="_new">Introduction</a></li>
        <li><a href="#features" target="_new">Features</a></li>
        <li><a href="#installation" target="_new">Installation</a></li>
        <li><a href="#usage" target="_new">Usage</a></li>
        <li><a href="#dependencies" target="_new">Dependencies</a></li>
        <li><a href="#contributing" target="_new">Contributing</a></li>
        <li><a href="#license" target="_new">License</a></li>
    </ul>
    <h2>Introduction</h2>
    <p>Web scraping is a powerful technique for extracting valuable information from websites, and Xpath plays a crucial
        role in locating specific elements within the HTML structure. Our scraper is designed to demonstrate how to
        leverage Xpath to extract lists of data from Vocabulary.com webpage efficiently.</p>
    <h2>Features</h2>
    <ul>
        <li>Easy-to-use Python web scraper.</li>
        <li>Scrapes multiple web pages simultaneously.</li>
        <li>Utilizes Xpath for precise data extraction.</li>
        <li>Saves the scraped data into a local file for further analysis.</li>
    </ul>
    <h2>Installation</h2>
    <ol>
        <li>Clone this repository to your local machine:</li>
    </ol>
    <pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">git <span class="hljs-built_in">clone</span> https://github.com/Anonymate054/VOC-SCR.git
</code></div></div></pre>
    <ol start="2">
        <li>Navigate to the project directory:</li>
    </ol>
    <pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash"><span class="hljs-built_in">cd</span> VOC-SCR
</code></div></div></pre>
    <ol start="3">
        <li>Install the required dependencies:</li>
    </ol>
    <pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"></div><div class="p-4 overflow-y-auto">pip install -r requirements.txt
</code></div></div></pre>
    <h2>Usage</h2>
    <p>To use the web scraper, follow these steps:</p>
    <ol>
        <li>Open the <code>Scraper_Voc.ipynb</code> file in your preferred Python notebook environment.</li>
        <li>Replace the <code>HOME_URL</code> list with the URLs of the webpage with the list of vocabulary you want to scrape.</li>
        <li>Run the scraper:</li>
    </ol>
    <pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">code Scraper_Voc.ipynb
</code></div></div></pre>
    <ol start="5">
        <li>The scraper will retrieve the lists of data from the provided web pages and save the results to a file named
            <code>voc_list.txt</code>.
        </li>
    </ol>
    <p><strong>Note:</strong> Please be respectful when scraping websites and make sure you are complying with their
        terms of service and policies.</p>
    <h2>Dependencies</h2>
    <p>The project relies on the following Python libraries:</p>
    <ul>
        <li>requests</li>
        <li>lxml</li>
        <li>os</li>
    </ul>
    <p>These dependencies are listed in the <code>requirements.txt</code> file and will be installed during the setup
        process. (in process)</p>
    <h2>Contributing</h2>
    <p>We welcome contributions to improve and expand this web scraper. If you have any suggestions, bug fixes, or
        additional features to add, feel free to open an issue or submit a pull request. We appreciate your support!</p>
    <h2>License</h2>
    <p>This project is licensed under the MIT License - see the <a href="LICENSE" target="_new">LICENSE</a> file for
        details.</p>
    <hr>
    <p>Happy scraping! If you encounter any issues or have any questions, please don't hesitate to reach out. Thank you
        for using our Web Scraper!</p>
</div>
