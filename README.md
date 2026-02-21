docker exec openclaw-gateway node openclaw.mjs config set gateway.trustedProxies '["0.0.0.0/0"]'
docker exec openclaw-gateway node openclaw.mjs devices approve --latest
# openclaw
