require "bundler/gem_tasks"

desc "Fetch file from https://github.com/buberdds/angular-bootstrap-colorpicker"
task :fetch do
  source = "https://raw.github.com/buberdds/angular-bootstrap-colorpicker/master/js/bootstrap-colorpicker-module.js"
  target = "vendor/assets/javascripts/angular-bootstrap-colorpicker.js"
  sh "curl #{source} > #{target}"

  source = 'https://raw.github.com/buberdds/angular-bootstrap-colorpicker/master/css/colorpicker.css'
  target = 'vendor/assets/stylesheets/angular-bootstrap-colorpicker.css'
  sh "curl #{source} > #{target}"
end

