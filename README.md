# Focus One V0.1.2

Focus on one thing at a time.

## Changes in this build
- Screen Wake Lock is requested during a running focus session, released on pause/end/completion, and requested again on resume/return.
- New **Complete task** button saves elapsed focus time as a completed session.
- Completion screen adds **Start a new task**.
- Activities can now be deleted with the × control. Deleting an activity does not erase historical sessions.
- Service-worker cache bumped to v0.1.2.

## Publish update
Upload these files to the root of your existing GitHub repository and replace the old versions. Commit to the branch already connected to GitHub Pages. Your existing URL stays the same.

If the installed Home Screen app briefly shows the old UI, fully close it and reopen it after GitHub Pages finishes deploying.
