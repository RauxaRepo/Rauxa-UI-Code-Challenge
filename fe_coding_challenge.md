Functional spec
---------------

Prototype the following project:

#### GitHub Followers

Create a service that allows for a user to search for a GitHub username. On a
successful search return, display the user's GitHub handle, follower count, and
a list of the user's followers (just the avatar is fine). Since some users (e.g.
`mrdoob`, `holman`, etc.) have many thousands of followers, GitHub only returns
a portion of the followers with each request. Create a "load more" button that,
when clicked, fetches the next payload of followers. This button should persist
until there are no more pages of followers to fetch.

Information on the GitHub API is available here: [GitHub API](https://developer.github.com/v3/)

The UX/UI is totally up to you. If you like, get creative and add additional
features a user might find useful!

[Coding Guidelines can be found here.](coding_guidelines.md)
