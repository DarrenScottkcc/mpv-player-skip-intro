# mpv-player-skip-intro
Automatically skips intro/outro based on title.

# Installation
Place skip_intro.lua in your mpv scripts folder.

Place skip_intro.conf in your mpv script-opts folder.

# Usage
-- Enable or disable automatic chapter skipping

skip_chapter=yes

-- Intro (OP) chapter name patterns — separated by |

op_patterns=OP|[Oo]pening$|^[Oo]pening:|[Oo]pening [Cc]redits

-- Ending (ED) chapter name patterns

ed_patterns=ED|[Ee]nding$|^[Ee]nding:|[Ee]nding [Cc]redits|[Cc]redits
