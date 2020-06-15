# Puppet
# Regenerating puppet cert
2) On Master, to clean the cert type: puppet cert clean agent_fqdn
3) On Agent, type: rm -rf /etc/puppetlabs/puppet/ssl and restart the puppet.
4) On Master, type: puppet cert sign agent_fqdn
