# erikbjorndahl
Twig https

Can someone please help me here, i cant get this search functions to work after i upgrade to twig 2.0 and my site to https...

Whats wrong?

<form action="{{ absolute_url('/api/sort') }}" method="post" class="form -search js-suggestive-search js-container-search grid -pad">
							<div class="grid__column">
								<label for="input-search" class="form__label">Vad vill du sortera?</label>
							</div>
							<div class="grid__column -desktop--6 -tablet--8 -mobile--12">
								<input type="search" name="query" id="input-search" placeholder="Sök" class="form__input">
							</div>
							<div class="grid__column -desktop--2 -tablet--2 -mobile--12">
								<button class="button">Sök</button>
							</div>

							<div class="js-container-search-result"></div>

						</form>
