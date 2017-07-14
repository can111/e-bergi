# e-bergi

e-bergi is a tech blog which resides [here](http://e-bergi.com).

This repo is an attempt to swap its setup for [Hugo](https://gohugo.io).

Since e-bergi is a system with many editors and authors, a `bergi-cms` is expected to mount the static generator.

## run

`git clone` then `hugo server`.

Most Linux distributions and FreeBSD have `hugo` as a package.

## contribute

Here is a rough **roadmap** for anyone who wants to help:

- [x] generate author profiles and articles
	- [x] author profiles with their respective articles
	- [x] multiple authors
	- [x] single article page
	- [x] author term page: a list of all authors
- [x] generate the index page, about page, categories
	- [x] index
	- [ ] ~~about~~ not clear what to put there
	- [x] categories
	- [ ] ~~category term page~~ no one uses that.

- [ ] dress pages
	- [ ] introduce correlated images for articles
	- [ ] figure out a way of navigation
	- [ ] set up an index layout
	- [ ] author and article pages
		- [ ] profile picture for author
		- [ ] author box under article

- [ ] bring tags

- [ ] archives
	- [ ] pagination for archives?

- [ ] start making cms

See the [rationale](RATIONALE.md) file for gotchas in the code.

licensed under MPLv2.
