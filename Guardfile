guard 'haml', :output => 'public', :input => 'src', :run_at_start => true do
  watch %r{^src/.+(\.html\.haml)}
end

guard 'compass', :output => 'public/stylesheets' do
  watch %r{^src\/(.*)\.s[ac]ss}
end

guard 'coffeescript', :input => 'src/coffeescripts', :output => 'public/javascripts'
