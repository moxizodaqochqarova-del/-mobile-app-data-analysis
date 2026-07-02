 Project: Mobile App Data Analysis — What Makes an App Popular?
Goal: Help a company (that builds free, ad-supported apps) decide what type of app to build next, since more users = more ad revenue.
What you did, step by step:

Loaded the data — two datasets: Apple App Store apps and Google Play Store apps (CSV files)
Cleaned the data:

Removed rows with missing/incomplete data (mismatched column count)
Detected and removed duplicate app entries, keeping the version with the highest review count (most recent/reliable)
Filtered out non-English apps using a character-detection function
Filtered to keep only free apps, since that matches the company's business model


Analyzed the data:

Built frequency tables to find the most common app genres/categories
Calculated the average number of users per genre — using rating counts as a proxy for installs on the App Store, and actual install numbers on Google Play


Key findings:

On the App Store, top genres (Reference, Music, Social Networking) are dominated by a few giant apps like the Bible app, Spotify, and Facebook
On Google Play, top categories (Communication, Video Players, Social) are dominated by apps like WhatsApp and Messenger
Your conclusion: these top spots aren't realistic targets for a new developer, since the high averages come from a handful of massive, already-dominant apps — meaning the recommendation likely points toward a different, less saturated genre being the smarter opportunity
