all: build

build: clean
	gem build ex42.gemspec

clean:
	rm -f exercise_42-*.gem

test:
	find bin -type f -print0 | xargs -0 -n1 -I__ ruby -c __
	find lib -type f -print0 | xargs -0 -n1 -I__ ruby -c __
