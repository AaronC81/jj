This is my fork of the [Jujutsu version control system](https://github.com/jj-vcs/jj).

On top of Jujutsu, it has:

* @gusinacio's LFS branch ([PR](https://github.com/jj-vcs/jj/pull/7098)/[repo](https://github.com/gusinacio/jj/tree/lfs))
* Completions for [Clink](https://chrisant996.github.io/clink/clink.html) using my [`clap_complete_clink`](https://github.com/AaronC81/clap_complete_clink) crate
* A new setting, `aaronc81.case-insensitive-gitignore`, which makes the contents of `.gitignore` apply case-insensitively (false by default)
