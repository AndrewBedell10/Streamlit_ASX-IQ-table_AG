import streamlit as st
import pandas as pd

# Create a sample DataFrame
data = {
    "Ticker": ["AAPL", "GOOGL", "MSFT", "AMZN", "FB"],
    "Company": ["Apple Inc.", "Alphabet Inc.", "Microsoft Corp.", "Amazon.com Inc.", "Meta Platforms, Inc."],
    "CFO": [100, 200, 150, 180, 220],
    "CFI": [120, 220, 180, 200, 240],
    "CFF": [80, 150, 130, 160, 170],
    "Cash Balance": [50000, 80000, 70000, 60000, 90000],
    "Cash Cover (#Qs)": [2.5, 3.2, 2.8, 3.0, 3.5]
}

df = pd.DataFrame(data)

# Display the DataFrame as a table using Streamlit
st.write("### Company Data Table")
st.table(df)
