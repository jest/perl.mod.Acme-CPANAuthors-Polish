# NAME

Acme::CPANAuthors::Polish - We are Polish CPAN authors

Acme::CPANAuthors::Polish - jesteśmy autorami-Polakami modułów na CPAN

# VERSION

version 0.03

# SYNOPSIS

	use Acme::CPANAuthors->new('Polish');
	
	my $number = $authors->count;
	my @ids = $authors->id;
	my @distros = $authors->distributions("ZBY");
	my $url = $authors->avatar_url("PWES");
	my $kwalitee = $authors->kwalitee("TADZIK");
	my $name = $authors->name("PMURIAS");

See documentation for [Acme::CPANAuthors](https://metacpan.org/pod/Acme::CPANAuthors) for more details.

# DESCRIPTION

This class provides a hash of Polish CPAN authors' PAUSE ID and name to
be used with the `Acme::CPANAuthors` module.

# MAINTENANCE

If you are a Polish CPAN author not listed here, please send us your ID/name
via email or bug tracer so we can keep this module up to date.

Also, if you are not a Polish CPAN author listed here, also notify us and
we will remove your name.

# SEE ALSO

[Acme::CPANAuthors](https://metacpan.org/pod/Acme::CPANAuthors) - Main class to manipulate the authors, also in this module

Module code inspired by:

[Acme::CPANAuthors::British](https://metacpan.org/pod/Acme::CPANAuthors::British)

[Acme::CPANAuthors::Russian](https://metacpan.org/pod/Acme::CPANAuthors::Russian)

# AUTHOR

Przemyslaw Wesolek <jest@go.art.pl>

# COPYRIGHT AND LICENSE

This software is Copyright (c) 2013 by Przemyslaw Wesolek.

This is free software, licensed under:

    The Artistic License 2.0 (GPL Compatible)
