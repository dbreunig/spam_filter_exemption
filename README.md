# Spam Exemption Filters

This repository manages a file of Gmail filter rules for political campaign emails. Campaigns and affiliated groups buy and share email lists to solicit donations and other support from people. Often, these solicitations are undesired and irrelevant. 

For example, a national political party you support may decide to share your email with an affiliated candidate you don't support. Or: someone may enter your email erroneously or maliciously when supporting a campaign. In either case, your email is now part of a collaborative and shared file, passed around from campaign to campaign. 

Previously, the worst offenders of this practice -- who shotgunned out email after email to broad, irrelevant lists -- found themselves banished to spam folders after enough recipients flagged their missives as unwanted. But now, Google is making [a change](https://www.axios.com/2022/09/19/gmail-pilot-campaign-email-spam)

>Google is launching a pilot program to keep emails from political campaigns from going to users' spam folders this week, the company told Axios.
>
>...
>
>Gmail users may start seeing a lot more political emails in their inboxes, partly a result of Google bowing to pressure from conservatives who claimed the company marked Republican emails as spam more often than others.
>
>...
>
>Google asked the Federal Election Commission in June if a program that would let campaigns emails bypass spam filters, instead giving users the option to move them to spam first, would be legal under campaign finance laws.
>
>Despite hundreds of negative comments submitted to the FEC arguing against it, the FEC approved the program in August. Eligible committees, abiding by security requirements and best practices as outlined by Google, can now register to participate.
>
>...
>
>"We expect to begin the pilot with a small number of campaigns from both parties and will test whether these changes improve the user experience, and provide more certainty for senders during this election period," José Castañeda, a Google spokesperson, told Axios. "We will continue to listen and respond to feedback as the pilot progresses."
>
>...
>
>Once political campaigns are enrolled in Google’s pilot program, they will no longer be affected by Gmail’s standard forms of spam detection, though Gmail will keep scanning messages for phishing and malware.

Users will be presented with a more prominant 'unsubscribe' button, but who knows how effective this will be given the proliferation of these shared list.

This repository is an attempt to get ahead of this noise. It contains a file named `span_exemption_filters.xml` that will be updated as others file pull requests or issues. 

### To use this file: 

- Download it to your computer.
- Open the Gmail website and click the gear icon in the upper right corner.
- Click the "See all settings" button.
- Select the "Filters and Blocked Addresses" tab.
- Below any existing filters you may have, there is blue text reading "Import filters". Click this.
- Browse to select the downloaded file. Then click the button "Open file".
- Import all the rules or uncheck any you'd rather not use.
- Voila. You have your inbox back.

If I'm being too slow to push changes to this file _or_ you disagree with the list in any way: please fork this repo and start your own!

(Currently there is one filter in the file from the first PAC I found in my spam folder. I will be adding more later and perhaps a companion `csv` file with the rules and any notes in a more readable format.)