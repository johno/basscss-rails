require 'bundler/gem_tasks'
require 'fileutils'

task :update do
  puts 'Updating basscss files'
  # exec('npm i --save basscss-sass --prefix ./')
  FileUtils.remove_dir('app/assets/stylesheets/basscss')
  FileUtils.mkdir('app/assets/stylesheets/basscss')
  exec('cp node_modules/basscss-sass/*.scss app/assets/stylesheets/basscss')
end
