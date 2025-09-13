# Creepy Features

## Dashboard Pro Features

The Creepy dashboard offers a suite of "Pro" features designed to provide advanced control and insights for server administrators. Each feature is accessible through a dedicated page within the dashboard and is typically configured on a per-guild basis. The core logic for these features resides in specialized components within the `@/components/dashboard/pro/` directory.

### Severity & Punishment Settings

This feature provides a highly configurable, points-based moderation system designed to automate and standardize punishment for rule violations. Administrators can precisely define a spectrum of **Severity Levels**, each assigned a specific point value (e.g., Minimal: 1 point, Critical: 18 points). This granular control allows for a nuanced approach to different types of infractions. Crucially, the system enables the configuration of **Automated Punishments**. Administrators can set various point thresholds that, when reached by a user, automatically trigger specific actions like warnings, temporary mutes (with configurable durations), temporary bans, and even permanent bans. This comprehensive system streamlines moderation workflows, ensuring consistent rule enforcement and reducing manual burden.

### Profanity Filter Settings

This comprehensive profanity filtering system empowers administrators to maintain a clean and appropriate chat environment by automatically detecting and managing unwanted language. The core functionality includes a master switch to **Enable/Disable the Profanity Filter** for the entire guild. When enabled, the system can **Automatically Delete Messages** containing filtered words. For accountability, a **Log Channel ID** can be specified to record all deleted messages and user infractions. A key feature is the **Automated User Reply** system, allowing administrators to send warnings with pre-defined templates (funny, intense, professional) or custom messages, optionally including a GIF. Powerful **Custom Filtering** allows adding specific words or sentences, and **Ignored Channels** can be set for flexibility.

### Onboarding Settings

This feature provides comprehensive tools for customizing the welcome and goodbye experience for members joining or leaving your server, fostering a more engaging and organized community. For **Welcome Messages**, administrators have granular control: they can enable/disable them, specify a **Dedicated Welcome Channel**, craft **Custom Welcome Messages** using dynamic placeholders like `{{user}}`, and even choose to send a **Direct Message Option** for a more personal greeting. Similarly, for **Goodbye Messages**, the feature offers enable/disable toggles, a **Dedicated Goodbye Channel**, and **Custom Goodbye Messages** with `{{user}}` support. These settings collectively allow server administrators to create a seamless and welcoming entry point for new members and a respectful farewell for those who leave.

### Mood Settings

This unique and advanced "Tier 2 Pro feature" allows server administrators to profoundly influence the personality and communication style of Creepy's AI-generated responses within their guild. Instead of a generic bot, Creepy can adapt its tone to match the desired atmosphere of the server. Administrators can select from a variety of **Pre-defined Mood Presets**, including "Neutral," "Happy," "Grumpy," "Mysterious," "Sarcastic," and "Formal." The chosen mood directly impacts the **AI Tone Influence**, ensuring that all AI-generated content, from general chat responses to automated messages, aligns with the selected persona. This feature provides a powerful way to personalize the bot's presence, making it feel more integrated and responsive to the server's unique community culture.

### Auto Responder Settings

This feature empowers administrators to create highly customizable automated responses, effectively allowing for the creation of custom commands or keyword-triggered replies within their guild. This is invaluable for automating frequently asked questions, providing quick information, or creating engaging interactive elements. The core of this feature is the ability to **Create Custom Responders**. For each responder, administrators define a "trigger" (the word or phrase the bot listens for) and a "response" (what the bot says in reply). Crucially, the system offers **Flexible Match Types** to control how precisely the trigger needs to match a user's message: "Exact Match," "Contains Word," or "Starts With." The intuitive interface allows for **Dynamic Management** of these responders, enabling easy addition or removal.

### Automated Moderation Settings

This feature provides a robust set of tools for automated moderation, significantly reducing the manual workload on server administrators and ensuring consistent enforcement of rules. The core functionality is the ability to **Enable Auto-Moderation**, which allows Creepy to automatically apply punishments based on the points system configured in the Severity settings. To prevent unintended actions, the system includes a **Fail-Safe Approval Role** for kicks and bans. For flexibility, administrators can define **Ignored Roles & Channels** that are exempt from automated moderation. A powerful tool for combating spam is **Account Age Verification**, allowing setting a **Minimum Account Age** and choosing an **Action for Underage Accounts** (No Action, Kick, or Ban). Finally, administrators can customize the **Command Prefix** for the bot.

### Analytics Settings

This feature provides comprehensive insights into server activity and bot usage, empowering administrators with data-driven decision-making to optimize their community. The dashboard presents **Key Performance Indicators (KPIs)** at a glance, including total messages, active members, and commands used over the last 7 days, offering a quick overview of server health. For deeper analysis, the **Channel Activity Visualization** displays messages per channel, allowing administrators to specify **Monitored Channel IDs**. A **Daily Server Activity Trends** line chart visualizes messages per day, helping identify patterns. The **Command Usage Breakdown** pie chart illustrates popular commands. Crucially, the system leverages **Real-time Data Updates** through Server-Sent Events (SSE), ensuring administrators always have access to the most current information for timely decision-making.

### Subscription Management

This feature provides a clear and intuitive interface for users to manage their "Pro" subscription, which is essential for unlocking all the advanced dashboard functionalities. Users can easily **Choose Subscription Tier**, with options for Tier 1 and Tier 2, each offering varying levels of access and pricing. The system offers **Flexible Billing Cycles**, allowing users to opt for either monthly or annual payments, with annual plans incentivized by a discount. A notable inclusion is **Redemption Code Support**, enabling temporary free access. The component is designed with **Integrated Payment Gateway** functionality, specifically mentioning Google Pay (though currently in beta). The **Transparent Pricing** display dynamically updates the cost based on the selected tier and billing cycle, ensuring clarity for the user.
