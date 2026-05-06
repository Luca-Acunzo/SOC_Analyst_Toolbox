# Wildcard
Adding an asterisk \* to the end of the text, will return any event that starts with the word. 
*Example*: fail\*   
# Booleans
- **AND**: *Example:* fail\* **AND** pass\* 
- **OR**: *Example:* fail\* **OR** pass\* 
- **NOT**: *Example:* fail\* **NOT** pass\*  
#### Order of evaluation
1. **NOT**
2. **OR**
3. **AND**
**Parentheses** can be used to control the order of evaluation. Splunk will first evaluate the terms in the **().**

