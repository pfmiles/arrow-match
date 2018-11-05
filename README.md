# arrow-match
* Sequence pattern matcher at O(n) speed, never backtrace, that's what an 'arrow' mean.
* Performing the match with deterministic-push-down-automata.
* Configurable disambiguity policies, thus, support 'ealiest-match' or 'longest-match' or both at the same time, or any arbitrary disambiguity tweaks you want.
* It's general purposed sequence pattern matcher, thus it doesn't assume what is really matched upon, it works on the abstract concept of 'sequence'.
