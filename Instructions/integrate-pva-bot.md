Power Virtual Agents (PVA) enables building a bot with little to no coding necessary, which opens up opportunities for subject matter experts to develop bots without developer assistance. These bots might be answering customer service questions, providing information on an order, or answer internal employee benefits questions. After a bot has been built, it's often the developer's job to take that bot and integrate it into an app or a website.

In this exercise, you'll import an already built bot into PVA, publish it, and add it to Teams.

> [!IMPORTANT]
> Power Virtual Agents access is limited to work and school email addresses. You can sign up with one of those addresses for a trial at the [Power Virtual Agents](https://powervirtualagents.microsoft.com/) landing page if you don't have access already. Personal email addresses are not allowed for trials at this time.

## Download bot .zip

To get the bot you'll use for this exercise, you'll need to download the bot you'll then import into Power Apps.

1. [Download the bot](https://aka.ms/ai102pvabot) from the Github repository. You'll need this `.zip' to import your bot later.

## Import your bot

A bot has already been built for you, and you just need to import it.

1. Go to the [Power Apps](https://make.powerapps.com/) page and log in
1. In the top bar there is a dropdown for **Environment** - make sure you're in a good environment for your company or school (such as a sandbox) or create your own if you have permissions to do so
1. On the left pane at the bottom, select **Solutions**
1. Above the list of solutions, select **Import solution**
1. Select the `AI102PVA_1_0_0_1.zip` file from where you downloaded the file to previously, and click Next
1. View the details about the solution you're importing, and then select Import
1. Importing may take a few minutes, and will provide details once it completes. Close that window
1. Select the **Contoso customer service** chatbot from the list to open the PVA portal
1. Once opened, you can test your bot in the left pane

## Publish your bot

After your bot is imported, you need to publish it through the PVA portal.

1. Go to the **Publish** page on the left
2. Select **Publish**, which may take a couple minutes

## Deploy your bot to Teams

Your bot is most useful if users can chat with it! Here we'll deploy your bot to Microsoft Teams, but a similar pattern is followed for other channels or custom apps and websites.

1. Go to the **Settings** page, and select **Channels**
2. Select **Microsoft Teams**, and select **Turn on Teams**
3. Select **Open bot** button under the *Bot Preview* section
4. Add your bot to teams - Teams will either launch for you, or you can use the web app
5. Log in to Teams, select **Add bot**, and ask your bot  for a "store location" to find Microsoft stores

## Deploy your bot elsewhere

Depending on your school or organization's policies, you may be able to view the bot in more channels, such as a demo or custom website. Give it a try to see how that experience is.

1. Go to **Settings > Security** and select **Authentication**
1. Select **No authentication**, and click **Save**
1. Publish your bot again on the **Publish** tab
1. Go to **Settings > Channels**, and select **Demo website**
1. Copy the URL provided, and click **Save**
1. Navigate to the URL, and chat with your bot in a sample webpage!

Alternatively, you can choose **Custom website** from the list of channels, and will get an embed code that looks similar to the following:

```html
<!DOCTYPE html><html><body><iframe src="<your-bot-url>" frameborder="0" style="width: 100%;height: 100%"></iframe></body></html>
```
