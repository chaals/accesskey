# accesskey
This is [a draft alternative specification](http://chaals.github.io/accesskey/index.src.html) for a proposed replacement for the accesskey section in HTML. It has now been proposed to the Web Incubator Community Group as an item for further development, so discussion can be fragmented between filing issues here, or [talking about it there](http://discourse.wicg.io/t/user-interaction-with-web-apps/1177).

The rationale is that interaction for web applications at the moment commonly introduces unexpected changes to the way a user agent behaves, hijacking functions that users rely on. 
This is an inevitable result of using javascript to define the interaction. 
Without a standard mechanism for knowing what specific interaction behaviours an author has requested, nor for authors to request a behaviour and allow the user agent to remap it, there is no way to do conflict resolution.

The purpose of working on the `accesskey` attribute is in part to help resolve this situation: As a markup attribute reflected in the DOM, `accesskey` offers naive authors a simple way to extend interaction without the need for them to write script, while providing a framework which is exposed to script authors.

This approach has been discussed in various places for a long time. The document provides an outline of those discussions, but needs to point to more background for many readers.
