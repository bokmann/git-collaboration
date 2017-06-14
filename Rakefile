task :default do
  exec("mdspell -r *.md **/*.md")
  fail if $? != 0
end

