guard :shell do
  watch /koans\/(.*)/ do |m|
    n m[0], 'Changed'
    `./r`
  end
end
