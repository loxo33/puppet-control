# Puppet Repos


forge "http://forge.puppetlabs.com"
mod "garethr/docker", 'v5.3.0'
mod "garethr/hiera_etcd", 'v0.2.0'
mod "garethr/kubernetes", 'v0.4.0'
mod "jfryman/nginx", :latest
mod "cristifalcas/etcd", :latest

# Modules from Git
# Examples: https://github.com/puppetlabs/r10k/blob/master/doc/puppetfile.mkd#examples
#mod 'apache',
#  :git    => 'https://github.com/puppetlabs/puppetlabs-apache',
#  :commit => '83401079053dca11d61945bd9beef9ecf7576cbf'

mod 'profiles'
    :git            => 'https://github.com/loxo33/profiles.git',
    :branch         => ':control_branch',
    :default_branch => 'production'
