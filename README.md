# pickem-points-generator

A simple app built to generate random yahoo fantasy football pickem weighted points.

Contents:
- Web interface with simple buttons for generating random weighted points
  - Prompts for # of games (n)
    - Values generated will be integers between 1 and n
  - Prompts to generate number
    - Accept and re-generate?
      - This removes the accepted value from being randomly generated again
    - Regenerate?
      - Recycles the current value into the potential generated values
  - Button always there to "reset"
- Persistent storage for generated value tracking
  - Likely a simple file to start with
  - This will allow the application to resume if user is interrupted
- CLI script to launch web app
  - Prompt for "New" or "Resume" (if detected)?