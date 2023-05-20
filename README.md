# Join Nasqueron

## Goal

The "Join Nasqueron" micro site is specifically tailored for internship
and mentoring opportunities at Nasqueron, as part of our outreach initiatives.

## Content

The microsite allows to create a focused and streamlined experience
that caters specifically to potential interns. This allows them to easily
navigate and access the relevant information they need to make an informed
decision about applying for an internship or mentorship program with Nasqueron.

The subdomain join.nasqueron.org implies that's an entry point for beings
interested to join Nasqueron, so it can be evolved to serve as a portal
for open source contributions and free culture project too.

This is a static site built with Gulp, based on the ZURB Foundation template,
updated and maintained as part of our Upsection effort.

## Installation

To install this site:

```
$ git clone https://devcentral.nasqueron.org/source/join-www.git
```

Then open the folder in your command line, and install the needed dependencies:

```bash
cd join-www
yarn install
```

Finally, run `yarn start` to run Gulp. Your finished site will be created in a
folder called `dist`, viewable at this URL:

```
http://localhost:8000
```

To create compressed, production-ready assets, run `yarn run build`.

For Nasqueron, this is done by a Jenkins CD task.
