
# moto6333

<h2 align="center">You can reach me at:</h2>

<p align="center">
  <a href="https://willmoto.com">
    <img src="https://d2fltix0v2e0sb.cloudfront.net/dev-badge.svg" alt="My Personal Website" height="30" width="30">
  </a>

  ```java
package motosgithub;

import org.bukkit.ChatColor;
import org.bukkit.entity.Player;
import org.bukkit.event.EventHandler;
import org.bukkit.event.Listener;
import org.bukkit.event.player.AsyncPlayerChatEvent;
import org.bukkit.plugin.java.JavaPlugin;

public class Main extends JavaPlugin implements Listener {
	@EventHandler
	public void onPlayerChat(AsyncPlayerChatEvent e) {
		Player p = e.getPlayer();
		if (e.getMessage().contains("info")) {
			e.setCancelled(true);
			p.sendMessage(ChatColor.DARK_RED + "Hello! My name is Moto I write some code mostly java I know some other stuff tho");
		    p.sendMessage(ChatColor.DARK_RED + " Java , JS, PHP");
		}

	}
}
```
  
</p>


<h2 align="center">Github stats :bar_chart:</h2>

<h4 align="center">Visitor's count :eyes:</h4>

<p align="center"><img src="https://profile-counter.glitch.me/{moto6333}/count.svg" alt="AnhellO :: Visitor's Count" /></p>

<h4 align="center">Top langs :tongue:</h4>

<p align="center"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=moto6333&langs_count=10&theme=tokyonight&layout=compact" alt="AnhellO :: Top Langs" /></p>

<h4 align="center">Profile stats :musical_keyboard:</h4>

<p align="center"><img src="https://github-readme-stats.vercel.app/api?username=moto6333&show_icons=true&theme=synthwave" alt="AnhellO :: Profile Stats" /></p>


