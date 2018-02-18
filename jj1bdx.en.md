# Rediscovering Ruby as mruby and Elixir

25 years ago in 1993, my primary programming language was C, and I thought I could survive without learning other languages. The rise of scripting language was much faster than I thought, however.

At the beginning of the 21st Century, I noticed a relatively new programming language called Ruby. I didn't like the syntax, and it was hard to learn, so I was dismissing Ruby for a long time. In fact, I still don't know much about Ruby except for tweaking HomeBrew scripts. Being a primary language for HomeBrew on macOS is, nevertheless, an excellent example of how Ruby is practical and useful. I even used portupgrade for FreeBSD too.

On the other hand, for a couple of years, I've been getting familiar with two languages significantly affected by Ruby: mruby and Elixir.

mruby is nice because it's small and concise. mruby is also domain-specific for two major applications: embedded systems and systems programming, both of which intrigue me the most for many years. [I even ported a small portion of code from Ruby to mruby for faster anomaly detection](https://github.com/matsumotory/mruby-matrix/pull/1).

And Elixir. I've been spending 10 years with Erlang, and Elixir has been my favorite language for Web programming due to the similarity of the core semantics with Erlang. I was surprised when I learned that many core parts of Elixir were derived from Ruby, such as the template language Eex, and the interpreter Iex. While there are still many significant semantic differences between Ruby and Elixir, I have to admit Ruby has influenced how Elixir ecosystem is shaped.

The rise of mruby and Elixir suggests a major direction for the future of Ruby: concurrent programming. I think the architects of Ruby including Matz and Koichi Sasada are already aware of this. Ruby without the giant lock and capable of handling multiple processor cores will surely be a quantum leap for the language and the ecosystem.

Last of all, congratulations on the 25th anniversary of Ruby.

# Kenji Rikitake

Kenji Rikitake is a software engineer working on computers since 1974. His recent interests in programming include the BEAM ecosystem of Erlang and Elixir programming languages and rediscovering object-oriented programming systems.

In many social networking systems including GitHub, Kenji's handle is `@jj1bdx`, the lower-cased callsign of his primary amateur radio station since 1976.
