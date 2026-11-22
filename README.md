# Brigadier
un MCP Security Gateway en Python (FastAPI, transport Streamable HTTP) placé entre un client agentique et ses serveurs MCP. La médiation et la journalisation doivent impérativement résider dans la passerelle et non dans les serveurs MCP cibles, car un serveur compromis ne peut pas être considéré comme fiable pour rapporter ses propres actes.
