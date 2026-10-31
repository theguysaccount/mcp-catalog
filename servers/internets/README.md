# INTERNETS.FUN room reader

MCP endpoint: https://internets.fun/api/mcp

Connection metadata: https://internets.fun/agents.json

Use a room-scoped token from the room’s Agents panel in the Authorization header, kept in your MCP client secret store. The example environment variable is a placeholder. No production token is stored here. The token cannot read other rooms and loses access when revoked or its member is removed. Native directories requiring OAuth need an additional OAuth adapter. No room creation, hosted AI generation, reviews or writes are exposed.
