# Python-AI-Unique-Name-generator
A small python utility that uses AI to generate  especial and distinctive startup name ideas subject to given descriptions.
In addition to the above, the utility checks for domain name availability based on the generated company names.
It can be used by any company founder or a startup to find the perfect business/organization/company name. For parents, only use this if you desire your childs name to be that of a startup or parent company name :)

## Installation

### Prerequisites

- Python >= Python 3.6 
- `pip` :- for package installation

## Notes:
- Remember to **Set up your OPENAI key** using the env variable:
```
export OPENAI_API_KEY="your_api_key"  # On Windows, use `set OPENAI_API_KEY=your_api_key`
```
- To start, run the main namegen file with a description of what your company is using the ```--prompt``` flag as below:
```bash
python namegen.py --prompt "A company for meeting plumbers with the appropriate clientbase" --tld="com"
```

## Extra Options
- You can specify names to check for availability using ```--names``` option
- Save generated names withe the ```--output``` option, providing an output filename.

