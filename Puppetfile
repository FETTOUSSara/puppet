
forge 'https://forge.puppet.com'

 # Modules from the Puppet Forge
 # Versions should be updated to be the latest at the time you start
 #mod 'puppetlabs/inifile', '5.0.1'
 mod 'puppetlabs/apache', '8.2.1'
 mod 'puppetlabs/stdlib',  '7.0.1'
 mod 'puppetlabs/concat',  '7.0.1'

# # Modules from Git
# Examples: https://github.com/puppetlabs/r10k/blob/master/doc/puppetfile.mkd#examples
 mod 'apache',
   git:    'https://github.com/puppetlabs/puppetlabs-apache',
     commit: '1b6f89afdde0df7f9433a163d5c4b5328eac5779'
#
#     #mod 'apache',
#     #  git:    'https://github.com/puppetlabs/puppetlabs-apache',
#     #  branch: 'docs_experiment'
#
     moduledir 'thirdparty'
     mod 'puppetlabs-apache', '8.2.1'
     mod 'puppetlabs/ntp',:latest
     mod 'puppetlabs/stdlib','0.10.0'
#
#     # Modules from Git
#     # # Examples: https://github.com/puppetlabs/r10k/blob/master/doc/puppetfile.mkd#examples
#
     mod 'site_data_1',
       :git => 'git@example.com:site_data_1.git',
           :install_path => 'hieradata'
           mod 'site_data_2',
             :git => 'git@example.com:site_data_2.git'
               :install_path => ' '
