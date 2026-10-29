# Joboostr

Find jobs in Czechia and remote opportunities through your Joboostr account, directly in Claude. Review job details and interactive cards, save jobs, hide unwanted recommendations, and keep application progress in the same account you use on the Joboostr website.

With active Joboostr Pro and separate resume approval, create a resume from your factual experience, tailor a copy to a selected job, change its content or design, save it to your account, and download a PDF produced by the real Joboostr CV Builder. Your original remains available when you tailor a copy.

Save a job you found elsewhere to your private Tracking page, including its application link, company and useful source context. It starts in Favourite and Not applied; saving never submits an application. Job-management approval is required.

With separate approval for saved application materials, keep job-specific resumes, cover letters, answers, comments and next steps in your account, then continue across devices or assistants. Resume operations also require their own resume permission.

## Connect

Install the Joboostr plugin in Claude. Open its **Connectors** tab, add or connect Joboostr, and sign in to your existing Joboostr account. In Claude Code, use the supported MCP sign-in flow. You never need to paste a password or access token into a conversation.

Job reading, job management, resume management and saved application materials have separate permissions. Installing the plugin does not grant access to your account. Review the requested permissions during sign-in. Joboostr checks account ownership and membership on each action. If an action needs permission your connection lacks, reconnect Joboostr through Claude’s connector settings and explicitly approve the required access.

For Claude Code, install from Joboostr’s public marketplace:

```text
/plugin install joboostr --marketplace joboostr/joboostr-claude
```

## Try it

- Find up to five product designer jobs in Prague, Czechia.
- Show remote software engineer jobs in Czechia posted this week.
- Save the first returned job and hide the second.
- Add this outside vacancy to my private Tracking, preserving its application link, description, location and salary facts.
- Show my current application progress for these jobs.
- Tailor a copy of my saved resume to the job I selected, then give me its PDF download and editing links.
- Change my selected resume to another available template while keeping the same facts.
- How many more Joboostr jobs can I view today?

Available facts and filters depend on your Joboostr account access. Job search shares the same allowance across connected assistants: 100 distinct jobs per day, resetting at midnight in Prague. Reopening a job already returned that day does not consume another slot. Resume operations do not add job-search allowance. A PDF download link expires after ten minutes; ask Claude to export the current saved revision again if necessary.

Interactive cards depend on the Claude surface. If a surface does not display them, Claude can use the same tools and returned Joboostr links. Opening Apply does not send an application. The plugin does not contact employers, make purchases or submit applications.

## Privacy and support

This package contains instructions, the Joboostr icon and the address of the existing Joboostr service. It runs no local server, command, install hook or background task and includes no credentials. Claude sends selected tool arguments to `https://mcp.joboostr.com/mcp` after you connect. Search arguments contain job preferences, not your full resume or personal contact details. Separately authorized resume actions read or write your selected account documents; export uses Joboostr’s existing CV Builder. Claude handles the conversation under its own terms.

[Joboostr](https://www.joboostr.com/en/jobs) · [Setup](https://www.joboostr.com/en/jobs) · [Assistant privacy](https://www.joboostr.com/en/assistant-privacy) · [Terms](https://www.joboostr.com/en/podminky) · [Support](https://www.joboostr.com/en/kontakt)

Package rights are reserved (`UNLICENSED`). Publishing these integration files does not license the Joboostr service or its data for redistribution.
