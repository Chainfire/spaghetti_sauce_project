# Spaghetti Sauce Project

If you're going to actually use anything part of this project, do not
forget to read the *Licenses* section.

## About

It's not exactly a secret I have been slowly moving away from the
Android root community for some time now (2015-ish?). At some point I
stated I was considering publishing some of my tricks and releasing the
sources for some of my code. I have always kept the intention of
doing so.

Alas, I have been quite busy with other projects and days turned to
months turned to years. But as at least *one* release is (finally)
coming up, the time to write this up is now.

Though most of my code is now largely outdated, I do think there are
some tricks used here and there that other (potential) developers of
root apps may still find interesting. And that is ultimately the only
real goal of releasing any source code: transferring knowledge.

Then again, this specific set of developers is known to continuously
reinvent the wheel without looking at prior efforts, so this might
all be for naught anyway :)

I make no commitments to *what* will be released or *when*, nor should
anyone be under the impression that anything will actively be
*maintained*.

Furthermore I make no claims to the code's *quality* or
*maintainability*. It's not called the *Spaghetti Sauce Project*
because it *doesn't* contain spaghetti code, obviously.

#### Hic sunt dracones

I've been toying with Android since the 1.x days, so I have a lot of
old code (that nevertheless works-for-me), and once something works
I happily reuse it. But Android has changed a lot over the years,
and so have the recommended ways of doing things.

Most of my code hasn't been built with open sourcing in mind,
and as my apps have (virtually) always been free-time single-developer,
comments and proper refactoring are sparse, and code debt is
plentiful.

What I'm trying to say here is that if you're looking for shining
examples of good code or how to do state-of-the-art Android development,
you should be reading the docs and tutorials on the Android site
instead. The goal here is to show how some things involving root were
done, not how to develop a modern app.

You should in particular take care not to copy any of my UI code/xml
constructs. Aside from finding it absolutely dreadful to create and thus
spending as little time on it as possible, even my newest root app
predates the first release of the Design Support Library. Things are
done differently nowadays.

Unless otherwise specified, it should be assumed nothing has even been
properly tested beyond Android 7.0.

## Licenses

Unless otherwise specified in the individual projects, all code part
of the Spaghetti Sauce Project is licensed as follows:

Copyright &copy; Jorrit 'Chainfire' Jongma

#### Libraries

Libraries by default use the [Apache License version 2.0](https://www.apache.org/licenses/LICENSE-2.0),
referred to APLv2 hereafter.

I would have preferred to use a license that would also require
sharing back the sources of modifications, but neither the LGPL nor
the GPL with classpath exception are technically good fits for Android
libraries.

As such I'm merely kindly requesting you share back the sources of
your modifications, if any.

#### Apps

Apps by default use the [GNU General Public License version 3.0](https://www.gnu.org/licenses/gpl-3.0.en.html),
referred to as GPLv3 hereafter.

I have no strong reason for picking v3 over v2 other than that v2 is
allegedly not truly compatible with APLv2, which a lot of open sourced
Android code is licensed as, and who wants that headache?

I would have preferred a license prohibiting forkers from uploading
modifications to the Play Store and/or profiting off the work
completely, but such licenses are frowned upon and in short supply.

What I am trying to limit here is people just running off with the
project as a whole or with minor changes.

Note: As many fear how viral the GPL can be, you are (unless otherwise
specified in the project) explicitly granted the rights to learn from
my code licensed as GPLv3 and implement that knowledge elsewhere, as
well as taking small excerpts and treating them as if they were
licensed as APLv2, *providing* in both cases that I am credited for my
work.

#### Attribution

For exact details, consult the license texts. The following is just
a quick non-legally-binding summary.

For both APLv2 and GPLv3, redistributing source code requires you to
maintain or augment the existing copyright notices.

For redistribution in binary form:

When using a library covered by the APLv2 in your app, credits
are required *only* if the project contains a NOTICE file, the contents
of which you are required to convey (see section 4d of the
[license text](https://www.apache.org/licenses/LICENSE-2.0)). If a
NOTICE file is not present (or empty), credits are still always
appreciated!

When redistributing an app covered by the APLv2 or GPLv3,
both licenses require you to maintain existing copyright notices.

Additionally see my note above in the *Apps* section regarding
attribution requirements when taking knowledge or excerpts from
apps covered by the GPLv3.
