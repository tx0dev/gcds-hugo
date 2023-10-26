# GCDS-hugo

Testing the water with the alpha [GC Design System](https://design-system.alpha.canada.ca) from the CDS.

## Background

In the past few weeks, there's a few thought that came around

### Why this?

it doesn't depend on jquery and it's using _modern_ web design paradigm.

### Hugo vs Jekyll

I don't like Jekyll, correction, I don't like Ruby and bundler, They are slow, heavy and the interaction with it's process is annoying.

I've used hugo in the past and it's incredibly fast and way ligher than dealing with Ruby. It's also usable with a single compiled binary in pretty much anything, probably even your toaster.

### And WET?

[WET](https://wet-boew.github.io/wet-boew/index-en.html) still depend on jquery, something that the Internet collectively decide should die, but they are sticking with it, and they are _still_ using version 2. Even the Canada.ca version is using a version from 2016, a 7 years old version. _depressing_.

So yeah, WET can die, or evolve out of their jquery dependency. There are currently effort get rid of older jquery for [WET 5](https://wet-boew.github.io/wet-boew-documentation/research/2018-4-wet5-project.html), but it's still very much experimental and no movement [since 2018](https://wet-boew.github.io/wet-boew-documentation/research/2018-6-wb5-exploration-1.html#combined-prototype-1).

### But JavaScript everywhere

Yeah, well, _Welcome to Web 2.0_. 

I'm tired of every site making JavaScript mandatory to render what is essentially a static website. But apparently basic and minimal static HTML is too complicated /s.

## Use

Download/obtain [hugo](https://gohugo.io/) through your favorite source, mine was from nixpkgs.

then run `hugo serve` and you'll have a website. That's it, no dependency to deal with.

## This is VERY experiemental

I'm not a web designer/programmer. I'm literally ripping appart the sample page from the [gcds-components](https://github.com/cds-snc/gcds-components), loading the JS from their CDN, and breaking hugo templating engine.... a lot.

### What's missing

Everything? Here's what I've tried, or know I'll want in this:

- [ ] Breadcrumb using .Ancestors
- [ ] Mermaid rendering
- [ ] Code block (with code highlighter would be nice)

### From upstream

- [ ] Data table (it's listed as coming soon)
