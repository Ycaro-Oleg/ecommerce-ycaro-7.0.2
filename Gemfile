source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.2"

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"

# Use postgresql as the database for Active Record
gem "pg", "~> 1.1"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 5.0"

# Bundle and transpile JavaScript [https://github.com/rails/jsbundling-rails]
gem "jsbundling-rails"

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails"

# Bundle and process CSS [https://github.com/rails/cssbundling-rails]
gem "cssbundling-rails"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

gem 'devise'

gem 'simple_form'

gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

gem "bootsnap", require: false

group :development, :test do

  gem 'awesome_print'
  gem 'dotenv-rails' # Trabalha com variaveis de ambiente 
  gem 'factory_bot_rails' # Ferramenta para poder criar dados mais facilmente dentro de testes
  gem 'faker' # Construir e criar dados aleatorios para testes
  gem 'pry-rails' # Criar breakpoints da aplicação 
  gem 'rspec-rails' # framework para testes substituindo o minitest
  gem 'rubocop' # Prettier para rails 
end

group :development do
  
  gem "web-console"

end

group :test do
  
  gem "capybara"
  gem 'webmock'
  gem "selenium-webdriver"
  gem "webdrivers"
  gem 'database_cleaner' #Limpa o banco para que nao tenha dados comprometedores ao teste
  gem 'shoulda-matchers' #Sintaxe mais facil para escrita de testes
  gem 'simplecov' #Da um gráfico de quanto o projeto está testado
  gem 'vcr' #Criação de "fake requests"
end
