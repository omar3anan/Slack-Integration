# Slack-Integration
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slack Integration with Slack API</title>
</head>
<body>
    <h1>Setting Up Slack Integration using Slack API</h1>
    <h2>First Step: Create Slack App</h2>
    <p>1. Go to <a href="https://api.slack.com/" target="_blank">https://api.slack.com/</a></p>
    <p>2. Create a new workspace and provide a new name for your workspace.</p>
    <h2>Second Step: Configure App Permissions</h2>
    <p>1. Navigate to the OAuth & Permissions section.</p>
    <p>2. Scroll down to user token scope and choose the scope of permissions your app will need.</p>
    <h3>Permissions Used:</h3>
    <ul>
        <li>@slack/web-api - The official Slack Web API client for Node.js.</li>
        <li>Post message in Slack using Web Client - <a href="https://hooks.slack.com/service/{Channel path}" target="_blank">https://hooks.slack.com/service/{Channel path}</a></li>
        <li>GET all Message during inside the channel - web.conversations.history</li>
        <li>Search Query - Use the endpoint provided by Slack: <a href="https://slack.com/api/search.all" target="_blank">https://slack.com/api/search.all</a></li>
    </ul>
    <h2>After Categorizing the Question</h2>
    <p>The categorized team will send an email with a response. You can perform the following actions:</p>
    <ol>
        <li>Use the <code>@slack/web-api</code> to interact with Slack's Web API.</li>
        <li>Post messages in Slack using the Web Client at <a href="https://hooks.slack.com/service/{Channel path}" target="_blank">https://hooks.slack.com/service/{Channel path}</a>.</li>
        <li>GET all messages inside the channel using the <code>web.conversations.history</code> endpoint.</li>
        <li>Search for keywords using the endpoint provided by Slack: <a href="https://slack.com/api/search.all" target="_blank">https://slack.com/api/search.all</a></li>
        <li>Filter the question and find technical keywords inside the chat for a readme file in GitHub.</li>
    </ol>
    <p>Page 7</p>

</body>
</html>
