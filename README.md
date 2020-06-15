# Puppet
Regenerating puppet cert
On Master, to clean the cert type: puppet cert clean agent_fqdn
On Agent, type: rm -rf /etc/puppetlabs/puppet/ssl and restart the puppet.
On Master, type: puppet cert sign agent_fqdn
