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
  desc 'migrate changes to the databse'
  task :migrage => :environment do
    Student.create_table
  end
end

