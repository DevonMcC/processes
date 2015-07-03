NB.* processes.ijs: process monitoring utilities - relies on "pslist" for Windows.

NB.* watchTillStartNew: wait for new instance of process identified by "str"
NB.* watchTillDone: watch processes ID'd by string, waiting wtm except 1st;
NB.* joinSplitHdrTitles: last 2 titles are 2 words each: put each pair into 1 col.
NB.* getRawPsTbl: get pslist output as table w/headers improperly split.
NB.* noPsFound: no process found by "getRawPsTbl".
NB.* getPsTbl: get pslist table as enclosed mat w/cell per item.
NB.* isNum: 1 iff y is numeric, 0 if not
NB.* dsp: delete extra spaces: multiple, leading, trailing.
NB.* checkPsEquiv: check if two uses of getPsTbl return same set of processes.
