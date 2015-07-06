# mindshare
Stateless shared data model for distributed services.

## Overview

Mindshare exposes mutable resources to your backend implementation, while
distributing the immutable entities (in the REST interpretation of the term),
that represent your resources' payload, across your services.

This way, mindshare helps to enable _active_ data synchronization
between your services, while keeping transactional state entirely client-side.

## Credits

Git, CouchDB
