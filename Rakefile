namespace :greeting do
  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end

  desc 'outputs hola to the terminal'
  task :hola do
    puts "hola de Rake!"
  end
end

namespace :db do
  desc 'invokes the :environment task as a dependency'
    task :migrate => :environment

    end
end

task :environmet do
  require_relative './config/environment'
end
