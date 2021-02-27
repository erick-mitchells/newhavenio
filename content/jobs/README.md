# Job Post Instructions

---

Hey there! If you're a local-ish tech company looking to hire talent we at NewHaven.io would love to help out by putting some information about your organization and open role(s) on our website.

Just [clone this repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository), add your information to [this page](https://github.com/newhavenio/newhavenio/tree/master/content/jobs/jobs.yaml), and submit a pull request.

```markdown
- company: "NewHaven.IO"
  jobURL: "https://newhaven.io"
  jobTitle: "Community Moderator"
  location: "New Haven, CT // Remote"
  remote: "Yes"
  tech: "Slack, MeetUp, GatsbyJS"
  salary: "Volunteer"
  description: "We're looking for help with some community moderation. As vaccines keep rolling out we're looking at ways we can begin to breathe life back into the group. We want to wade back into holding some events and we're going to need help keeping an eye our Slack team and Meetup page. Over time we can fold whoever takes this role into our organizing and leadership teams. If you've gotten some value from IO in the past we'd love your help in carrying it forward."
```

Add information on your role(s) as a new object(s) at the bottom of the file. Here's an example:

```markdown
- company: "NewHaven.IO"
  jobURL: "https://newhaven.io"
  jobTitle: "Community Moderator"
  location: "New Haven, CT // Remote"
  remote: "Yes"
  tech: "Slack, MeetUp, GatsbyJS"
  salary: "Volunteer"
  description: "We're looking for help with some community moderation. As vaccines keep rolling out we're looking at ways we can begin to breathe life back into the group. We want to wade back into holding some events and we're going to need help keeping an eye our Slack team and Meetup page. Over time we can fold whoever takes this role into our organizing and leadership teams. If you've gotten some value from IO in the past we'd love your help in carrying it forward."
- company: "Your Company Name"
  jobURL: "URL to Your Site (or Job Post)"
  jobTitle: "Role Title"
  location: "Company Location // Remote?"
  remote: "Yes / No / For Now"
  tech: "Tech, In, Your, Stack"
  salary: "Estimated Salary (or Salary Range)"
  description: "A few sentence long blurb on what the job will entail, what the potential employee will be working on, and what specifically you're looking for."
```

Every attribute is required except for the salary. If you omit that line, the rendered role on our `/jobs` page will display "Salary Not Provided". Should a required attribute not be present in a PR, we'll work with you to ensure all the pertinent information is presented to our members.

You might see a `hidden: "true"` attribute for the example job post in the `jobs.yaml` file. That's just to exclude the example from the final rendered Jobs page, and you can leave that out of your YAML block.

Once we get the notification of your PR, check your formatting, and roll your change into the main branch: a Netlify build should kick off and deploy the updated version.

Please feel free to [join our Slack](https://newhaven.io) and contact any of us admins in the #organizing channel if there's anything else we might be able to do to help you hire local!

And please remember to take your role off this page and submit a new PR when you close out your search. We look forward to reviewing a celebratory PR with you!