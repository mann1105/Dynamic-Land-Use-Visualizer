A streamlit app that combines power of large language models(LLMs) with satellite imagery for interactive mapping to provide users a  comprehensive land use insights. It provides a user-friendly platform to compare various land cover datasets, including ESA WorldCover, ESRI Land Cover, and Dynamic World, offering a multi-perspective view of how the Earth's surface is transforming.
- Utilizes gemini LLM to interpret user queries about specific locations, events, or time periods and extracts parameters such as coordinates, dates, and context from user input.
- Results are displayed into a clear and informative summary, highlighting key trends, changes, and statistics related to the user's query.
- With the extracted data from user's query a visualization of land cover is displayed using google earth engine(gee).
- For eg. User enters query "Uttarakhand flood". LLM understands the context from the prompt template provided and it extracts the Longitude, Latitude, Event date(here 16/06/2013) and passes it to gee and displays the land cover from 15/06/2013-20/06/2013.


Working demo with limited functionality: https://www.youtube.com/watch?v=hVZhj6LZjTY 
