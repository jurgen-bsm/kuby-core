source 'https://rubygems.org'

gemspec

gem 'kube-dsl', git: 'git@github.com:jurgen-bsm/kube-dsl.git', branch: 'main'

group :development, :test do
  gem 'pry-byebug'
  gem 'rake'

  gem 'curdle', '~> 1.2'
  gem 'parlour', '~> 8.0'
  gem 'tapioca', '~> 0.7'
  gem 'sorbet-runtime', '= 0.5.11647'
  gem 'sorbet-static', '= 0.5.11647'
end

group :test do
  gem 'rspec', '~> 3.0'
end
