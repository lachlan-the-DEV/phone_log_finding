# Phone log Finding

I found a poorly worded log when looking at my phone logs, it states this:

Oct 23 16:49:39 iPhone bluetoothd[102] <Notice>: Done sending the reply now

Notice how it ends with "Done sending the reply now", this is poor wording, It should be something more like "Reply transmission completed successfully".

# But what caused this?
I think this may be from a dev who was bugfixing and forgot to change it back, or maybe the dev was inexperienced, I do not have enough evidence to come to any conclusion so for now this is a mystery.

# Should This Be Fixed?
In my opinion, no this should not be fixed as this is harmless and changing it may cause bugs.
