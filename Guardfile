guard 'haml', :output => 'public', :input => 'src' do
  watch %r{^src/.+(\.html\.haml)}
end

guard 'compass', :output => 'public/stylesheets' do
  watch('^src/(.*)\.s[ac]ss')
end

guard 'coffeescript', :input => 'src/coffeescripts', :output => 'public/javascripts'
