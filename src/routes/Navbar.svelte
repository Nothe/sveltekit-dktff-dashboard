<script>
	import logo from '$lib/images/svelte-logo.svg';
	import { page } from '$app/stores';

	let selectedTheme = 'dark' ;
	let collapsed = null;
	let isCollapsed = false;
	
	function setThemeDark() {
		selectedTheme = 'dark' ;
		console.log(selectedTheme)
	}	
	
		function setThemeLight() {
		selectedTheme = 'light' ;
		console.log(selectedTheme)
	}
	
	function setToggle() {
		console.log(toggles)
	}
	
	function handleCollapseToggleClick() {
  isCollapsed = !isCollapsed;
  updateCollapsedState();
}

function updateCollapsedState() {
  isCollapsed ? collapsed = 'collapsed': collapsed = null;
	console.log(collapsed)
}


</script>

<div class="container">
	<aside class="sidebar" theme={selectedTheme} {collapsed}>
		<button class="collapse-toggle" on:click={handleCollapseToggleClick}/>
		<section class="sidebar__section sidebar__section--title">
			<a href="#" class="logo">
				<svg
					id="logo"
					class="logo__svg"
					width="170"
					height="41"
					viewBox="0 0 170 41"
					fill="none"
					xmlns="http://www.w3.org/2000/svg"
				>
					<path
						d="M51.8601 28.138H63.8121V24.538H56.1081V10.978H51.8601V28.138Z"
						class="logo__text"
					/>
					<path
						d="M70.8932 25.738C69.1892 25.738 68.3012 24.25 68.3012 22.018C68.3012 19.786 69.1892 18.274 70.8932 18.274C72.5972 18.274 73.5092 19.786 73.5092 22.018C73.5092 24.25 72.5972 25.738 70.8932 25.738ZM70.9172 28.522C74.8772 28.522 77.4692 25.714 77.4692 22.018C77.4692 18.322 74.8772 15.514 70.9172 15.514C66.9812 15.514 64.3412 18.322 64.3412 22.018C64.3412 25.714 66.9812 28.522 70.9172 28.522Z"
						class="logo__text"
					/>
					<path
						d="M84.3237 32.386C86.1477 32.386 87.7557 31.978 88.8357 31.018C89.8197 30.13 90.4677 28.786 90.4677 26.938V15.85H86.7237V17.17H86.6757C85.9557 16.138 84.8517 15.49 83.2197 15.49C80.1717 15.49 78.0597 18.034 78.0597 21.634C78.0597 25.402 80.6277 27.466 83.3877 27.466C84.8757 27.466 85.8117 26.866 86.5317 26.05H86.6277V27.274C86.6277 28.762 85.9317 29.626 84.2757 29.626C82.9797 29.626 82.3317 29.074 82.1157 28.426H78.3237C78.7077 30.994 80.9397 32.386 84.3237 32.386ZM84.2997 24.562C82.8357 24.562 81.8757 23.362 81.8757 21.514C81.8757 19.642 82.8357 18.442 84.2997 18.442C85.9317 18.442 86.7957 19.834 86.7957 21.49C86.7957 23.218 86.0037 24.562 84.2997 24.562Z"
						class="logo__text"
					/>
					<path
						d="M98.166 25.738C96.462 25.738 95.574 24.25 95.574 22.018C95.574 19.786 96.462 18.274 98.166 18.274C99.87 18.274 100.782 19.786 100.782 22.018C100.782 24.25 99.87 25.738 98.166 25.738ZM98.19 28.522C102.15 28.522 104.742 25.714 104.742 22.018C104.742 18.322 102.15 15.514 98.19 15.514C94.254 15.514 91.614 18.322 91.614 22.018C91.614 25.714 94.254 28.522 98.19 28.522Z"
						class="logo__text"
					/>
					<path
						d="M105.884 28.138H109.796V15.85H105.884V28.138ZM105.884 14.146H109.796V10.978H105.884V14.146Z"
						class="logo__text"
					/>
					<path
						d="M111.494 32.194H115.406V26.866H115.454C116.222 27.898 117.35 28.522 118.934 28.522C122.15 28.522 124.286 25.978 124.286 21.994C124.286 18.298 122.294 15.49 119.03 15.49C117.35 15.49 116.15 16.234 115.31 17.338H115.238V15.85H111.494V32.194ZM117.926 25.498C116.246 25.498 115.286 24.13 115.286 22.138C115.286 20.146 116.15 18.634 117.854 18.634C119.534 18.634 120.326 20.026 120.326 22.138C120.326 24.226 119.414 25.498 117.926 25.498Z"
						class="logo__text"
					/>
					<path
						d="M130.655 28.522C133.871 28.522 136.247 27.13 136.247 24.442C136.247 21.298 133.703 20.746 131.543 20.386C129.983 20.098 128.591 19.978 128.591 19.114C128.591 18.346 129.335 17.986 130.295 17.986C131.375 17.986 132.119 18.322 132.263 19.426H135.863C135.671 17.002 133.799 15.49 130.319 15.49C127.415 15.49 125.015 16.834 125.015 19.426C125.015 22.306 127.295 22.882 129.431 23.242C131.063 23.53 132.551 23.65 132.551 24.754C132.551 25.546 131.807 25.978 130.631 25.978C129.335 25.978 128.519 25.378 128.375 24.154H124.679C124.799 26.866 127.055 28.522 130.655 28.522Z"
						class="logo__text"
					/>
					<path
						d="M141.561 28.498C143.265 28.498 144.345 27.826 145.233 26.626H145.305V28.138H149.049V15.85H145.137V22.714C145.137 24.178 144.321 25.186 142.977 25.186C141.729 25.186 141.129 24.442 141.129 23.098V15.85H137.241V23.914C137.241 26.65 138.729 28.498 141.561 28.498Z"
						class="logo__text"
					/>
					<path
						d="M150.75 28.138H154.662V21.25C154.662 19.786 155.382 18.754 156.606 18.754C157.782 18.754 158.334 19.522 158.334 20.842V28.138H162.246V21.25C162.246 19.786 162.942 18.754 164.19 18.754C165.366 18.754 165.918 19.522 165.918 20.842V28.138H169.83V20.146C169.83 17.386 168.438 15.49 165.654 15.49C164.07 15.49 162.75 16.162 161.79 17.65H161.742C161.118 16.33 159.894 15.49 158.286 15.49C156.51 15.49 155.334 16.33 154.566 17.602H154.494V15.85H150.75V28.138Z"
						class="logo__text"
					/>
					<path
						fill-rule="evenodd"
						clip-rule="evenodd"
						d="M20.6841 40.138C31.7298 40.138 40.6841 31.1837 40.6841 20.138C40.6841 9.09234 31.7298 0.138031 20.6841 0.138031C9.63837 0.138031 0.684082 9.09234 0.684082 20.138C0.684082 31.1837 9.63837 40.138 20.6841 40.138ZM26.9234 9.45487C27.2271 8.37608 26.1802 7.73816 25.2241 8.41933L11.8772 17.9276C10.8403 18.6663 11.0034 20.138 12.1222 20.138L15.6368 20.138V20.1108H22.4866L16.9053 22.0801L14.4448 30.8212C14.1411 31.9 15.1879 32.5379 16.1441 31.8567L29.491 22.3485C30.5279 21.6098 30.3647 20.138 29.246 20.138L23.9162 20.138L26.9234 9.45487Z"
						class="logo__icon"
					/>
				</svg>
			</a>
		</section> 


		<section class="sidebar__section sidebar__section--search">
			<div class="search">
				<input type="text" class="search__input" placeholder="Search..." />
				<button class="search__button" />
			</div>
		</section>

		<section class="sidebar__section sidebar__section--menu">
			<h2 class="sidebar__subtitle">Menu</h2>
			<nav class="nav">
				<ul class="nav__list">
					<li class="nav__item" aria-current={$page.url.pathname === '/' ? 'page' : undefined}>
						<a href="/" class="nav__link">
							<span class="nav__icon nav__icon--home" />
							<span class="nav__text">Home</span>
						</a>
					</li>
					<li class="nav__item" aria-current={$page.url.pathname === '/search' ? 'page' : undefined}>
						<a href="/search" class="nav__link">
							<span class="nav__icon nav__icon--search" />
							<span class="nav__text">Search</span>
						</a>
					</li>
					<li class="nav__item" aria-current={$page.url.pathname === '/replay' ? 'page' : undefined}>
						<a href="/replay" class="nav__link">
							<span class="nav__icon nav__icon--activity" />
							<span class="nav__text">Replay</span>
							<span class="nav__count">10</span>
						</a>
					</li>
					<li class="nav__item" aria-current={$page.url.pathname === '/job' ? 'page' : undefined}>
						<a href="/job" class="nav__link">
							<span class="nav__icon nav__icon--task" />
							<span class="nav__text">Job</span>
							<span class="nav__count">21</span>
						</a>
					</li>
					<li class="nav__item" aria-current={$page.url.pathname === '/about' ? 'page' : undefined}>
						<a href="/about" class="nav__link">
							<span class="nav__icon nav__icon--notifications" />
							<span class="nav__text">Notifications</span>
						</a>
					</li>
				</ul>
			</nav>
		</section>

		<hr class="divider" />

		<section class="sidebar__section sidebar__section--settings">
			<nav class="nav">
				<ul class="nav__list">
					<li class="nav__item">
						<a href="#" class="nav__link">
							<span class="nav__icon nav__icon--settings" />
							<span class="nav__text">Settings</span>
						</a>
					</li>
					<li class="nav__item">
						<a href="#" class="nav__link">
							<span class="nav__icon nav__icon--report" />
							<span class="nav__text">Report</span>
						</a>
					</li>
					<li class="nav__item" aria-current={$page.url.pathname === '/' ? 'page' : undefined}>
						<a href="/about" class="nav__link">
							<span class="nav__icon nav__icon--support" />
							<span class="nav__text">Support</span>
						</a>
					</li>
				</ul>
			</nav>
		</section>

		<hr class="divider divider--transparent" />

		<section class="sidebar__section sidebar__section--groups">
			<h2 class="sidebar__subtitle">Group</h2>
			<nav class="nav">
				<ul class="nav__list">
					<li class="nav__item">
						<a href="#" class="nav__link">
							<span class="nav__circle nav__circle--green" />
							<span class="nav__text">DKTFF ADMIN</span>
							<span class="nav__chevron" />
						</a>
					</li>
					<li class="nav__item">
						<a href="#" class="nav__link">
							<span class="nav__circle nav__circle--blue" />
							<span class="nav__text">Design System</span>
							<span class="nav__chevron" />
						</a>
					</li>
					<li class="nav__item">
						<a href="#" class="nav__link">
							<span class="nav__circle nav__circle--yellow" />
							<span class="nav__text">Accessibility</span>
							<span class="nav__chevron" />
						</a>
					</li>
				</ul>
			</nav>
		</section>

		<section class="sidebar__section sidebar__section--theme">
			<div class="toggle">
				<input class="toggle__input" type="radio" id="light" name="theme" value="light" on:click={setThemeLight} />
				<label class="toggle__label" for="light">
					<span class="toggle__icon" />
					<span class="toggle__text">Light</span>
				</label>

				<input class="toggle__input" type="radio" id="dark" name="theme" value="dark" on:click={setThemeDark} checked />
				<label class="toggle__label" for="dark">
					<span class="toggle__icon" />
					<span class="toggle__text">Dark</span>
				</label>
			</div>
		</section>

		<section class="sidebar__section sidebar__section--account">
			<div class="account">
				<div class="account__details">
					<h4 class="account__name">Valentin De Smet</h4>
					<p class="account__email">valentin.desmet@decathlon.com</p>
				</div>
				<button class="account__exit" />
			</div>
		</section>
	</aside>
</div>

<style>
	* {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
		color: var(--color-text);
		font-family: sans-serif;
	}

	:root,
	::before,
	::after {
		--color-container: #e7e9eb;
		--color-blue: #1f5eea;
		--color-red: #e3494a;
		--color-green: #57b083;
		--color-yellow: #e9b64b;

		--font-size-x-small: 0.675rem;
		--font-size-small: 0.75rem;
		--font-size-normal: 0.875rem;

		--transition-speed-normal: 0.25s;

		--nav-icon-size: 1rem;
		--nav-circle-size: 0.5rem;

		--icon-search: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTkuNSwzQTYuNSw2LjUgMCAwLDEgMTYsOS41QzE2LDExLjExIDE1LjQxLDEyLjU5IDE0LjQ0LDEzLjczTDE0LjcxLDE0SDE1LjVMMjAuNSwxOUwxOSwyMC41TDE0LDE1LjVWMTQuNzFMMTMuNzMsMTQuNDRDMTIuNTksMTUuNDEgMTEuMTEsMTYgOS41LDE2QTYuNSw2LjUgMCAwLDEgMyw5LjVBNi41LDYuNSAwIDAsMSA5LjUsM005LjUsNUM3LDUgNSw3IDUsOS41QzUsMTIgNywxNCA5LjUsMTRDMTIsMTQgMTQsMTIgMTQsOS41QzE0LDcgMTIsNSA5LjUsNVoiIC8+PC9zdmc+');
		--icon-home: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTEyIDUuNjlMMTcgMTAuMTlWMThIMTVWMTJIOVYxOEg3VjEwLjE5TDEyIDUuNjlNMTIgM0wyIDEySDVWMjBIMTFWMTRIMTNWMjBIMTlWMTJIMjIiIC8+PC9zdmc+');
		--icon-activity: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTIyLDIxSDJWM0g0VjE5SDZWMTBIMTBWMTlIMTJWNkgxNlYxOUgxOFYxNEgyMlYyMVoiIC8+PC9zdmc+');
		--icon-task: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTE5LDE5SDVWNUgxNVYzSDVDMy44OSwzIDMsMy44OSAzLDVWMTlBMiwyIDAgMCwwIDUsMjFIMTlBMiwyIDAgMCwwIDIxLDE5VjExSDE5TTcuOTEsMTAuMDhMNi41LDExLjVMMTEsMTZMMjEsNkwxOS41OSw0LjU4TDExLDEzLjE3TDcuOTEsMTAuMDhaIiAvPjwvc3ZnPg==');
		--icon-users: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTEyLDJBMTAsMTAgMCAwLDAgMiwxMkExMCwxMCAwIDAsMCAxMiwyMkExMCwxMCAwIDAsMCAyMiwxMkExMCwxMCAwIDAsMCAxMiwyTTcuMDcsMTguMjhDNy41LDE3LjM4IDEwLjEyLDE2LjUgMTIsMTYuNUMxMy44OCwxNi41IDE2LjUsMTcuMzggMTYuOTMsMTguMjhDMTUuNTcsMTkuMzYgMTMuODYsMjAgMTIsMjBDMTAuMTQsMjAgOC40MywxOS4zNiA3LjA3LDE4LjI4TTE4LjM2LDE2LjgzQzE2LjkzLDE1LjA5IDEzLjQ2LDE0LjUgMTIsMTQuNUMxMC41NCwxNC41IDcuMDcsMTUuMDkgNS42NCwxNi44M0M0LjYyLDE1LjUgNCwxMy44MiA0LDEyQzQsNy41OSA3LjU5LDQgMTIsNEMxNi40MSw0IDIwLDcuNTkgMjAsMTJDMjAsMTMuODIgMTkuMzgsMTUuNSAxOC4zNiwxNi44M00xMiw2QzEwLjA2LDYgOC41LDcuNTYgOC41LDkuNUM4LjUsMTEuNDQgMTAuMDYsMTMgMTIsMTNDMTMuOTQsMTMgMTUuNSwxMS40NCAxNS41LDkuNUMxNS41LDcuNTYgMTMuOTQsNiAxMiw2TTEyLDExQTEuNSwxLjUgMCAwLDEgMTAuNSw5LjVBMS41LDEuNSAwIDAsMSAxMiw4QTEuNSwxLjUgMCAwLDEgMTMuNSw5LjVBMS41LDEuNSAwIDAsMSAxMiwxMVoiIC8+PC9zdmc+');
		--icon-search: url('data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/PjwhRE9DVFlQRSBzdmcgIFBVQkxJQyAnLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4nICAnaHR0cDovL3d3dy53My5vcmcvR3JhcGhpY3MvU1ZHLzEuMS9EVEQvc3ZnMTEuZHRkJz48c3ZnIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgMCAwIDUwIDUwIiBoZWlnaHQ9IjUwcHgiIGlkPSJMYXllcl8xIiB2ZXJzaW9uPSIxLjEiIHZpZXdCb3g9IjAgMCA1MCA1MCIgd2lkdGg9IjUwcHgiIHhtbDpzcGFjZT0icHJlc2VydmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiPjxyZWN0IGZpbGw9Im5vbmUiIGhlaWdodD0iNTAiIHdpZHRoPSI1MCIvPjxjaXJjbGUgY3g9IjIxIiBjeT0iMjAiIGZpbGw9Im5vbmUiIHI9IjE2IiBzdHJva2U9IiMwMDAwMDAiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLW1pdGVybGltaXQ9IjEwIiBzdHJva2Utd2lkdGg9IjIiLz48bGluZSBmaWxsPSJub25lIiBzdHJva2U9IiMwMDAwMDAiIHN0cm9rZS1taXRlcmxpbWl0PSIxMCIgc3Ryb2tlLXdpZHRoPSI0IiB4MT0iMzIuMjI5IiB4Mj0iNDUuNSIgeTE9IjMyLjIyOSIgeTI9IjQ1LjUiLz48L3N2Zz4=');
		--icon-notifications: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTEwIDIxSDE0QzE0IDIyLjEgMTMuMSAyMyAxMiAyM1MxMCAyMi4xIDEwIDIxTTIxIDE5VjIwSDNWMTlMNSAxN1YxMUM1IDcuOSA3IDUuMiAxMCA0LjNWNEMxMCAyLjkgMTAuOSAyIDEyIDJTMTQgMi45IDE0IDRWNC4zQzE3IDUuMiAxOSA3LjkgMTkgMTFWMTdMMjEgMTlNMTcgMTFDMTcgOC4yIDE0LjggNiAxMiA2UzcgOC4yIDcgMTFWMThIMTdWMTFaIiAvPjwvc3ZnPg==');
		--icon-settings: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTEyLDhBNCw0IDAgMCwxIDE2LDEyQTQsNCAwIDAsMSAxMiwxNkE0LDQgMCAwLDEgOCwxMkE0LDQgMCAwLDEgMTIsOE0xMiwxMEEyLDIgMCAwLDAgMTAsMTJBMiwyIDAgMCwwIDEyLDE0QTIsMiAwIDAsMCAxNCwxMkEyLDIgMCAwLDAgMTIsMTBNMTAsMjJDOS43NSwyMiA5LjU0LDIxLjgyIDkuNSwyMS41OEw5LjEzLDE4LjkzQzguNSwxOC42OCA3Ljk2LDE4LjM0IDcuNDQsMTcuOTRMNC45NSwxOC45NUM0LjczLDE5LjAzIDQuNDYsMTguOTUgNC4zNCwxOC43M0wyLjM0LDE1LjI3QzIuMjEsMTUuMDUgMi4yNywxNC43OCAyLjQ2LDE0LjYzTDQuNTcsMTIuOTdMNC41LDEyTDQuNTcsMTFMMi40Niw5LjM3QzIuMjcsOS4yMiAyLjIxLDguOTUgMi4zNCw4LjczTDQuMzQsNS4yN0M0LjQ2LDUuMDUgNC43Myw0Ljk2IDQuOTUsNS4wNUw3LjQ0LDYuMDVDNy45Niw1LjY2IDguNSw1LjMyIDkuMTMsNS4wN0w5LjUsMi40MkM5LjU0LDIuMTggOS43NSwyIDEwLDJIMTRDMTQuMjUsMiAxNC40NiwyLjE4IDE0LjUsMi40MkwxNC44Nyw1LjA3QzE1LjUsNS4zMiAxNi4wNCw1LjY2IDE2LjU2LDYuMDVMMTkuMDUsNS4wNUMxOS4yNyw0Ljk2IDE5LjU0LDUuMDUgMTkuNjYsNS4yN0wyMS42Niw4LjczQzIxLjc5LDguOTUgMjEuNzMsOS4yMiAyMS41NCw5LjM3TDE5LjQzLDExTDE5LjUsMTJMMTkuNDMsMTNMMjEuNTQsMTQuNjNDMjEuNzMsMTQuNzggMjEuNzksMTUuMDUgMjEuNjYsMTUuMjdMMTkuNjYsMTguNzNDMTkuNTQsMTguOTUgMTkuMjcsMTkuMDQgMTkuMDUsMTguOTVMMTYuNTYsMTcuOTVDMTYuMDQsMTguMzQgMTUuNSwxOC42OCAxNC44NywxOC45M0wxNC41LDIxLjU4QzE0LjQ2LDIxLjgyIDE0LjI1LDIyIDE0LDIySDEwTTExLjI1LDRMMTAuODgsNi42MUM5LjY4LDYuODYgOC42Miw3LjUgNy44NSw4LjM5TDUuNDQsNy4zNUw0LjY5LDguNjVMNi44LDEwLjJDNi40LDExLjM3IDYuNCwxMi42NCA2LjgsMTMuOEw0LjY4LDE1LjM2TDUuNDMsMTYuNjZMNy44NiwxNS42MkM4LjYzLDE2LjUgOS42OCwxNy4xNCAxMC44NywxNy4zOEwxMS4yNCwyMEgxMi43NkwxMy4xMywxNy4zOUMxNC4zMiwxNy4xNCAxNS4zNywxNi41IDE2LjE0LDE1LjYyTDE4LjU3LDE2LjY2TDE5LjMyLDE1LjM2TDE3LjIsMTMuODFDMTcuNiwxMi42NCAxNy42LDExLjM3IDE3LjIsMTAuMkwxOS4zMSw4LjY1TDE4LjU2LDcuMzVMMTYuMTUsOC4zOUMxNS4zOCw3LjUgMTQuMzIsNi44NiAxMy4xMiw2LjYyTDEyLjc1LDRIMTEuMjVaIiAvPjwvc3ZnPg==');
		--icon-report: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTEyLjM2LDZMMTIuNzYsOEgxOFYxNEgxNC42NEwxNC4yNCwxMkg3VjZIMTIuMzZNMTQsNEg1VjIxSDdWMTRIMTIuNkwxMywxNkgyMFY2SDE0LjQiIC8+PC9zdmc+');
		--icon-support: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTE5Ljc5LDE1LjQxQzIwLjc0LDEzLjI0IDIwLjc0LDEwLjc1IDE5Ljc5LDguNTlMMTcuMDUsOS44M0MxNy42NSwxMS4yMSAxNy42NSwxMi43OCAxNy4wNiwxNC4xN0wxOS43OSwxNS40MU0xNS40Miw0LjIxQzEzLjI1LDMuMjYgMTAuNzYsMy4yNiA4LjU5LDQuMjFMOS44Myw2Ljk0QzExLjIyLDYuMzUgMTIuNzksNi4zNSAxNC4xOCw2Ljk1TDE1LjQyLDQuMjFNNC4yMSw4LjU4QzMuMjYsMTAuNzYgMy4yNiwxMy4yNCA0LjIxLDE1LjQyTDYuOTUsMTQuMTdDNi4zNSwxMi43OSA2LjM1LDExLjIxIDYuOTUsOS44Mkw0LjIxLDguNThNOC41OSwxOS43OUMxMC43NiwyMC43NCAxMy4yNSwyMC43NCAxNS40MiwxOS43OEwxNC4xOCwxNy4wNUMxMi44LDE3LjY1IDExLjIyLDE3LjY1IDkuODQsMTcuMDZMOC41OSwxOS43OU0xMiwyQTEwLDEwIDAgMCwxIDIyLDEyQTEwLDEwIDAgMCwxIDEyLDIyQTEwLDEwIDAgMCwxIDIsMTJBMTAsMTAgMCAwLDEgMTIsMk0xMiw4QTQsNCAwIDAsMCA4LDEyQTQsNCAwIDAsMCAxMiwxNkE0LDQgMCAwLDAgMTYsMTJBNCw0IDAgMCwwIDEyLDhaIiAvPjwvc3ZnPg==');
		--icon-chevron: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTguNTksMTYuNThMMTMuMTcsMTJMOC41OSw3LjQxTDEwLDZMMTYsMTJMMTAsMThMOC41OSwxNi41OFoiIC8+PC9zdmc+');
		--icon-moon: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTE3Ljc1LDQuMDlMMTUuMjIsNi4wM0wxNi4xMyw5LjA5TDEzLjUsNy4yOEwxMC44Nyw5LjA5TDExLjc4LDYuMDNMOS4yNSw0LjA5TDEyLjQ0LDRMMTMuNSwxTDE0LjU2LDRMMTcuNzUsNC4wOU0yMS4yNSwxMUwxOS42MSwxMi4yNUwyMC4yLDE0LjIzTDE4LjUsMTMuMDZMMTYuOCwxNC4yM0wxNy4zOSwxMi4yNUwxNS43NSwxMUwxNy44MSwxMC45NUwxOC41LDlMMTkuMTksMTAuOTVMMjEuMjUsMTFNMTguOTcsMTUuOTVDMTkuOCwxNS44NyAyMC42OSwxNy4wNSAyMC4xNiwxNy44QzE5Ljg0LDE4LjI1IDE5LjUsMTguNjcgMTkuMDgsMTkuMDdDMTUuMTcsMjMgOC44NCwyMyA0Ljk0LDE5LjA3QzEuMDMsMTUuMTcgMS4wMyw4LjgzIDQuOTQsNC45M0M1LjM0LDQuNTMgNS43Niw0LjE3IDYuMjEsMy44NUM2Ljk2LDMuMzIgOC4xNCw0LjIxIDguMDYsNS4wNEM3Ljc5LDcuOSA4Ljc1LDEwLjg3IDEwLjk1LDEzLjA2QzEzLjE0LDE1LjI2IDE2LjEsMTYuMjIgMTguOTcsMTUuOTVNMTcuMzMsMTcuOTdDMTQuNSwxNy44MSAxMS43LDE2LjY0IDkuNTMsMTQuNUM3LjM2LDEyLjMxIDYuMiw5LjUgNi4wNCw2LjY4QzMuMjMsOS44MiAzLjM0LDE0LjY0IDYuMzUsMTcuNjZDOS4zNywyMC42NyAxNC4xOSwyMC43OCAxNy4zMywxNy45N1oiIC8+PC9zdmc+');
		--icon-sun: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTEyLDdBNSw1IDAgMCwxIDE3LDEyQTUsNSAwIDAsMSAxMiwxN0E1LDUgMCAwLDEgNywxMkE1LDUgMCAwLDEgMTIsN00xMiw5QTMsMyAwIDAsMCA5LDEyQTMsMyAwIDAsMCAxMiwxNUEzLDMgMCAwLDAgMTUsMTJBMywzIDAgMCwwIDEyLDlNMTIsMkwxNC4zOSw1LjQyQzEzLjY1LDUuMTUgMTIuODQsNSAxMiw1QzExLjE2LDUgMTAuMzUsNS4xNSA5LjYxLDUuNDJMMTIsMk0zLjM0LDdMNy41LDYuNjVDNi45LDcuMTYgNi4zNiw3Ljc4IDUuOTQsOC41QzUuNSw5LjI0IDUuMjUsMTAgNS4xMSwxMC43OUwzLjM0LDdNMy4zNiwxN0w1LjEyLDEzLjIzQzUuMjYsMTQgNS41MywxNC43OCA1Ljk1LDE1LjVDNi4zNywxNi4yNCA2LjkxLDE2Ljg2IDcuNSwxNy4zN0wzLjM2LDE3TTIwLjY1LDdMMTguODgsMTAuNzlDMTguNzQsMTAgMTguNDcsOS4yMyAxOC4wNSw4LjVDMTcuNjMsNy43OCAxNy4xLDcuMTUgMTYuNSw2LjY0TDIwLjY1LDdNMjAuNjQsMTdMMTYuNSwxNy4zNkMxNy4wOSwxNi44NSAxNy42MiwxNi4yMiAxOC4wNCwxNS41QzE4LjQ2LDE0Ljc3IDE4LjczLDE0IDE4Ljg3LDEzLjIxTDIwLjY0LDE3TTEyLDIyTDkuNTksMTguNTZDMTAuMzMsMTguODMgMTEuMTQsMTkgMTIsMTlDMTIuODIsMTkgMTMuNjMsMTguODMgMTQuMzcsMTguNTZMMTIsMjJaIiAvPjwvc3ZnPg==');
		--icon-logout: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTE2LDE3VjE0SDlWMTBIMTZWN0wyMSwxMkwxNiwxN00xNCwyQTIsMiAwIDAsMSAxNiw0VjZIMTRWNEg1VjIwSDE0VjE4SDE2VjIwQTIsMiAwIDAsMSAxNCwyMkg1QTIsMiAwIDAsMSAzLDIwVjRBMiwyIDAgMCwxIDUsMkgxNFoiIC8+PC9zdmc+');
	}

	.container {
		/*
        width: 100%;
		min-height: 100vh;
        */
		display: flex;
		align-items: center;
		justify-content: center;
		flex-direction: column;
		grid-area: navbar;
		background-color: var(--color-container);
	}

	.sidebar {
		--sidebar-width: 240px;

		width: var(--sidebar-width);
		background-color: var(--color-bg);
		border-radius: 0.5rem;
		padding: 0.5rem 0;
		height: 100vh;
		position: absolute;
		left: 0;
		top: 0;
	}

	.sidebar[theme='dark'] {
		--color-bg: #1c2536;
		--color-text: #fefefe;
		--color-surface: rgb(0 0 0 / 20%);
		--color-surface-alternative: rgb(255 255 255 / 8%);
	}

	.sidebar[theme='light'] {
		--color-bg: #ffffff;
		--color-text: #323842;
		--color-surface: rgb(100 100 100 / 8%);
		--color-surface-alternative: rgb(100 100 100 / 8%);
	}

	.sidebar__section {
		padding: 0.5rem 1rem;
	}

	.sidebar__subtitle {
		font-size: var(--font-size-small);
		font-weight: 500;
		opacity: 0.75;
		margin-bottom: 1rem;
	}

	.divider {
		width: calc(100% - 2rem);
		height: 1px;
		background-color: var(--color-surface-alternative);
		border: none;
		margin: 0.5rem 1rem 0.75rem;
	}

	.divider--transparent {
		background-color: transparent;
	}

	.logo__text {
		fill: var(--color-text);
	}

	.logo__icon {
		fill: var(--color-blue);
	}

	.search {
		with: 100%;
		position: relative;
	}

	.search__input {
		width: 100%;
		padding: 0.5rem 0.5rem 0.5rem 2rem;
		border-radius: 0.25rem;
		background-color: var(--color-surface);
		display: block;
		color: var(--color-text);
		position: relative;
		border: 1px solid transparent;
	}

	.search__input:focus {
		outline: none;
		border: 1px solid var(--color-text);
	}

	.search__button {
		width: auto;
		height: 100%;
		aspect-ratio: 1;
		display: block;
		position: absolute;
		top: 0;
		left: 0;
		border: none;
		background-color: var(--color-text);
		mask-position: center;
		-webkit-mask-position: center;
		mask-size: 50%;
		-webkit-mask-size: 50%;
		mask-repeat: no-repeat;
		-webkit-mask-repeat: no-repeat;
		mask-image: var(--icon-search);
		-webkit-mask-image: var(--icon-search);
	}

	.nav__list {
		list-style: none;
	}

	.nav__link {
		text-decoration: none;
		font-size: var(--font-size-normal);
		background-color: var(--color-bg);
		padding: 0.75rem 0.5rem;
		display: flex;
		align-items: center;
		justify-content: space-between;
		gap: 0.5rem;
		width: 100%;
		border-radius: 0.25rem;
	}

	.nav__icon {
		height: var(--nav-icon-size);
		width: var(--nav-icon-size);
		display: block;
		background-color: var(--color-text);
		mask-position: center;
		-webkit-mask-position: center;
		mask-size: contain;
		-webkit-mask-size: contain;
		mask-repeat: no-repeat;
		-webkit-mask-repeat: no-repeat;
		opacity: 0.75;
	}

	.nav__icon--home {
		mask-image: var(--icon-home);
		-webkit-mask-image: var(--icon-home);
	}

	.nav__icon--activity {
		mask-image: var(--icon-activity);
		-webkit-mask-image: var(--icon-activity);
	}

	.nav__icon--task {
		mask-image: var(--icon-task);
		-webkit-mask-image: var(--icon-task);
	}

	.nav__icon--users {
		mask-image: var(--icon-users);
		-webkit-mask-image: var(--icon-users);
	}

		.nav__icon--search {
		mask-image: var(--icon-search);
		-webkit-mask-image: var(--icon-search);
	}

	.nav__icon--notifications {
		mask-image: var(--icon-notifications);
		-webkit-mask-image: var(--icon-notifications);
	}

	.nav__icon--settings {
		mask-image: var(--icon-settings);
		-webkit-mask-image: var(--icon-settings);
	}

	.nav__icon--report {
		mask-image: var(--icon-report);
		-webkit-mask-image: var(--icon-report);
	}

	.nav__icon--support {
		mask-image: var(--icon-support);
		-webkit-mask-image: var(--icon-support);
	}

	.nav__circle {
		height: var(--nav-circle-size);
		width: var(--nav-circle-size);
		border-radius: 50%;
		margin: 0 0.25rem;
		flex-shrink: 0;
	}

	.nav__circle--green {
		background-color: var(--color-green);
	}

	.nav__circle--blue {
		background-color: var(--color-blue);
	}

	.nav__circle--yellow {
		background-color: var(--color-yellow);
	}

	.nav__text {
		flex-grow: 1;
	}

	.nav__count {
		padding: 0.125rem 0.4rem;
		border-radius: 0.5rem;
		background-color: var(--color-red);
		font-size: var(--font-size-x-small);
		color: white;
	}

	.nav__chevron {
		height: var(--nav-icon-size);
		width: var(--nav-icon-size);
		background-color: var(--color-text);
		mask-position: center;
		-webkit-mask-position: center;
		mask-size: contain;
		-webkit-mask-size: contain;
		mask-repeat: no-repeat;
		-webkit-mask-repeat: no-repeat;
		mask-image: var(--icon-chevron);
		-webkit-mask-image: var(--icon-chevron);
	}

	.toggle {
		width: 100%;
		background-color: var(--color-surface);
		border-radius: 0.25rem;
		padding: 0.25rem;
		display: grid;
		grid-template-columns: 1fr 1fr;
		grid-gap: 0.25rem;
	}

	.toggle__input {
		display: none;
	}

	.toggle__label {
		padding: 0.5rem;
		display: flex;
		align-items: center;
		justify-content: center;
		gap: 0.5rem;
		font-size: var(--font-size-normal);
		border-radius: 0.5rem;
		opacity: 0.5;
		cursor: pointer;
	}

	.toggle__input:checked + .toggle__label {
		background-color: var(--color-surface-alternative);
		opacity: 1;
		pointer-events: none;
	}

	.sidebar[theme='light'] .toggle__input:checked + .toggle__label {
		background-color: var(--color-bg);
	}

	.toggle__icon {
		content: '';
		height: 1rem;
		width: 1rem;
		display: block;
		-webkit-mask-position: center;
		mask-position: center;
		-webkit-mask-size: contain;
		mask-size: contain;
		-webkit-mask-repeat: no-repeat;
		mask-repeat: no-repeat;
		background-color: var(--color-text);
	}

	.toggle__label[for='light'] .toggle__icon {
		-webkit-mask-image: var(--icon-sun);
		mask-image: var(--icon-sun);
	}

	.toggle__label[for='dark'] .toggle__icon {
		-webkit-mask-image: var(--icon-moon);
		mask-image: var(--icon-moon);
	}

	.account {
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: space-between;
		gap: 0.5rem;
	}

	.account__avatar {
		height: 42px;
		width: 42px;
		border-radius: 50%;
		object-fit: cover;
		border: 2px solid var(--color-surface-alternative);
		cursor: pointer;
	}

	.account__details {
		display: flex;
		flex-direction: column;
		align-items: flex-start;
		justify-content: center;
		gap: 0.25rem;
		flex: 1 0 auto;
	}

	.account__name {
		font-size: var(--font-size-small);
		font-weight: 600;
	}

	.account__email {
		font-size: var(--font-size-small);
		font-weight: 400;
		opacity: 0.75;
	}

	.account__exit {
		height: 1.25rem;
		width: 1.25rem;
		display: block;
		background-color: var(--color-text);
		-webkit-mask-position: center;
		mask-position: center;
		-webkit-mask-size: contain;
		mask-size: contain;
		-webkit-mask-repeat: no-repeat;
		mask-repeat: no-repeat;
		-webkit-mask-image: var(--icon-logout);
		mask-image: var(--icon-logout);
		border: none;
		opacity: 0.5;
		cursor: pointer;
	}

	.collapse-toggle {
		position: absolute;
		top: 1.75rem;
		right: 0;
		height: 1.25rem;
		width: 1.25rem;
		background-color: var(--color-blue);
		border-radius: 50%;
		border: none;
		transform: translateX(50%) rotate(180deg);
		opacity: 1;
		cursor: pointer;
		transition: transform var(--transition-speed-normal) ease-in-out;
	}

	.sidebar[collapsed] .collapse-toggle {
		transform: translateX(50%) rotate(0deg);
	}

	.collapse-toggle::after {
		content: '';
		height: 100%;
		width: 100%;
		display: block;
		-webkit-mask-position: center;
		mask-position: center;
		-webkit-mask-size: contain;
		mask-size: contain;
		-webkit-mask-repeat: no-repeat;
		mask-repeat: no-repeat;
		-webkit-mask-image: var(--icon-chevron);
		mask-image: var(--icon-chevron);
		background-color: white;
	}

	/* Collapsed sidebar */
	.sidebar[collapsed] {
		--sidebar-width: 72px;
	}

	.sidebar[collapsed] .logo__text {
		display: none;
	}

	.sidebar[collapsed] .search__input {
		pointer-events: none;
	}

	.sidebar[collapsed] .search__button {
		left: 0.3rem;
	}

	.sidebar[collapsed] .sidebar__subtitle {
		display: none;
	}

	.sidebar[collapsed] .nav__link {
		padding: 0.75rem;
	}

	.sidebar[collapsed] .nav__text {
		display: none;
	}

	.sidebar[collapsed] .nav__count {
		display: none;
	}

	.sidebar[collapsed] .toggle {
		grid-template-columns: 1fr;
	}

	.sidebar[collapsed] .toggle__text {
		display: none;
	}

	.sidebar[collapsed] .account__details {
		display: none;
	}

	.sidebar[collapsed] .account__exit {
		display: none;
	}

	.props {
		margin-top: 3rem;
		font-size: 0.75rem;
		opacity: 0.75;
	}

	.props__link {
		color: var(--color-blue);
		text-decoration: none;
	}

	@media (hover: hover) {
		.nav__link:hover {
			background-color: var(--color-surface-alternative);
		}

		.toggle__label:hover {
			opacity: 1;
		}

		.account__exit:hover {
			opacity: 1;
		}

		.collapse-toggle:hover {
			opacity: 0.875;
		}

		.account__avatar:hover {
			border-color: var(--color-blue);
		}

		.props__link:hover {
			color: var(--color-green);
		}
	}
</style>
