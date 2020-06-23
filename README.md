# stemen.email
small website for the email domain i'm using

## process
I'm currently still in the phase of moving all my accounts over to this new email, so things aren't 100% worked out yet, but I thought I'd give an overview of how I'm using it.

Hosting email on fastmail allows you to accept email to everything at `foo@bar.stemen.email` where `foo` and `bar` are any strings (I'm sure there are some limitations to this, but I haven't looked into it too deeply). This feature allows me to

1. use a distinct email for every website/application I have to use
2. group emails by what they're used for

I group my emails by using the `bar` string, and get distinct emails by using the `foo` string. As an example if I was signing up for a web app run by a company called Buttress, I would use `buttress@app.stemen.email`. This serves a few purposes as far as I can tell. Unique emails for every application/mailing list/etc. means I cannot automatically be found in email lists that are from different companies/sources. This is great because it means it's harder to collate data about you into larger profiles.

It also means you don't have to trust companies/mailing lists to take you off mailing lists, because you can setup rules to send anything to `annoyinglist@list.stemen.email` directly to trash. Normally unsubscribing isn't a problem, but there are some skeevy companies, and maybe you'd even prefer not to tell them you're unsubscribing.

Lastly in terms of searching for email, you can search for emails sent to `.*@list.stemen.email` if you know you're searching for something that was on a mailing list which will help you narrow down your search. To be entirely clear, I'm not sure the second point of grouping emails is entirely necessary, or helpful, but I have feeling it might be. Still learning.

Anyway, here are the groups I use

- `stemen.email`: usually just `nate@stemen.email` which I give to people I know usually.
- `app.stemen.email`: definitely the most common which I use for all web applications, and native applications alike.
- `list.stemen.email`: mailing lists
- `mail.stemen.email`: anything mail related. backup emails for other emails, email forwarding, etc.
- `purchase.stemen.email`: one time purchases where I don't need an account