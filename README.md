## Postman Configuration Guide for GoRest API Testing

To ensure seamless API testing with GoRest, update the collection variables in Postman as follows:

1. **Starting Postman**:
   - Launch Postman on your computer. Download it from [Postman's official website](https://www.postman.com/downloads/) if needed.

2. **Accessing Collection Variables**:
   - Find the GoRest API testing collection in your Postman workspace.
   - Click on the ellipsis `...` beside the collection name and choose "Edit" to modify it.

3. **Updating the API Key**:
   - Obtain your personal API key from [GoRest's website](https://gorest.co.in) by signing in and navigating to the API section.
   - Under the 'Variables' tab in the edit dialog of the collection, locate the `api_key` variable.
   - Input your API key in the `CURRENT VALUE` column.

4. **Selecting a User ID**:
   - Go to [GoRest Users API](https://gorest.co.in/public/v2/users) and choose an ID.
   - Update the `id_env` variable's `CURRENT VALUE` in the same 'Variables' tab with the selected ID.

5. **Committing Changes**:
   - After updating the values, click 'Update' to save the changes to the collection.

7. **Running the Requests**:
   - With the variables updated, you can now run the requests in the collection that utilize these variables.

8. **Important Considerations**:
   - Your API key should be kept confidential.
   - Since GoRest data is refreshed daily, the user ID in the `id_env` variable may need to be updated regularly.

After following these steps, you'll have configured your Postman collection to interact with the GoRest API using your personal API key and chosen user ID.
