# Install dependencies

Best is to use a virtual environment:
```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

# Set the needed environment variables. 

The windsor.ai key can be obtained at https://onboard.windsor.ai after registering and granting access to the needed services.  The available datasources are listed here: https://windsor.ai/data-integration/
The OpenAI key is given registering at https://openai.com/join/
```
export WINDSOR_API_KEY="abcdefgh1234"
export OPENAI_API_KEY="YOUROPENAIKEY"
```
    
# Query data from Windsor.ai

```
python get_windsor_data.py facebook costs in october 2021 
```
```
Answer: [{'spend': 653127.51}]
```