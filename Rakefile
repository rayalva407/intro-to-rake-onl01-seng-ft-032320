namespace :greeting do
  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end

  desc 'outputs hola to the terminal'
  task :hola do
    puts "hola de Rake!"
  end
  
  task :environment do
    require_relative './config/environment'
  end
  
  desc 'drop into the pry console'
  task :console => :environment do
    Pry.start
  end
end

