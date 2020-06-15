# Puppet
# Regenerating puppet cert
1) On Master, to clean the cert type: puppet cert clean agent_fqdn
2) On Agent, type: rm -rf /etc/puppetlabs/puppet/ssl and restart the puppet.
3) On Master, type: puppet cert sign agent_fqdn
