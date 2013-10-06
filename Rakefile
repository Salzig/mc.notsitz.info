require 'rake'

task :deploy do
  sh 'jekyll build && scp -r _site/* minecraft.notsitz.info:/srv/www'
end
