
# Music Player

A modern music player application

##  Technologies

* **[Next.js](https://nextjs.org/)** 
* **[React](https://react.dev/)**
* **[Tailwind CSS](https://tailwindcss.com/)** 
* **[Zustand](https://zustand-demo.pmnd.rs/)** 
* **[Framer Motion](https://www.framer.com/motion/)** 
* **[React Testing Library](https://testing-library.com/docs/react-testing-library/)** 

## How to deploy

**Rename** the file `.env.local.example` to `.env.local` and **fill in** the following credentials

| Key | Source |
| :--- | :--- |
| `SPOTIFY_CLIENT_ID`| Get your ID from the **[Spotify Developer Dashboard](https://developer.spotify.com/dashboard)**. |
| `SPOTIFY_CLIENT_SECRET` | Get your Secret from the **[Spotify Developer Dashboard](https://developer.spotify.com/dashboard)**. |

Run the following commands in your terminal

```bash 
pnpm install 
pnpm run dev
```
The application will be accessible at `http://localhost:3000`.

### Testing

To run tests with **React Testing Library**:

```bash
pnpm test
```

