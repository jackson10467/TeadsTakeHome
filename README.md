# TeadsTakeHome
For the questions that follow, please create a public Git repository, push your code solutions there,
and include the repository link in your email along with your responses to Part 1. If you forget to do so,
please email it to us as soon as possible.
Instruction: Imagine you are assisting an advertiser in reviewing the status of their ad creatives. For
this task, we will simulate ad creatives using data from the /posts endpoint, where each post represents
an ad creative.
Endpoint: https://jsonplaceholder.typicode.com/posts
Your Task:
Create a simple HTML page with a button labeled “Review Ads”. Focus on functionality rather than
styling – a basic, unstyled page will be sufficient.
When the button is clicked, it should:
1. Fetch the list of creatives (posts).
2. Determine the review status of each creative based on its id:
• If the id is divisible by 3 → rejected
• Else if the id is divisible by 2 → approved
• Otherwise → pending
3. For each creative with a rejected status, convert its title to UPPERCASE.
4. Return a new array of objects, each containing:
• id
• title (modified if rejected)
• status (approved, pending, or rejected)
5. Print the resulting array to the console.
Don’t forget to include basic error handling in case the API request fails.