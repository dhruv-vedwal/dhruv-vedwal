# Fix

Replaced the failing split workflow with one job that generates all three profile cards using `shinpr/github-profile-stats`, then generates trophies with `ryo-ma/github-profile-trophy` without the unsupported `theme` input.
