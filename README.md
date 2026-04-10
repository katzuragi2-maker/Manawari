# Manawari export default function BeachResortHero() { return ( <section className="relative min-h-screen overflow-hidden bg-slate-950 text-white"> {/* Background image */} <div className="absolute inset-0 bg-cover bg-center" style={{ backgroundImage: "url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=1600&q=80')", }} />

{/* Dark overlay */}
  <div className="absolute inset-0 bg-black/65" />

  {/* Gradient glow */}
  <div className="absolute inset-0 bg-gradient-to-b from-slate-900/40 via-slate-950/60 to-slate-950" />

  {/* Navbar */}
  <header className="relative z-10 flex items-center justify-between px-6 py-5 md:px-16">
    <h1 className="text-2xl font-bold tracking-wide">Azure Coast</h1>
    <nav className="hidden gap-8 text-sm md:flex">
      <a href="#about" className="transition hover:text-cyan-300">About</a>
      <a href="#rooms" className="transition hover:text-cyan-300">Rooms</a>
      <a href="#activities" className="transition hover:text-cyan-300">Activities</a>
      <a href="#contact" className="transition hover:text-cyan-300">Contact</a>
    </nav>
    <button className="rounded-full border border-white/30 px-5 py-2 text-sm backdrop-blur-md transition hover:bg-white hover:text-slate-900">
      Book Now
    </button>
  </header>

  {/* Hero content */}
  <div className="relative z-10 flex min-h-[85vh] items-center px-6 md:px-16">
    <div className="max-w-3xl">
      <p className="mb-4 text-sm uppercase tracking-[0.35em] text-cyan-300">
        Luxury Beach Escape
      </p>

      <h2 className="mb-6 text-5xl font-bold leading-tight md:text-7xl">
        Discover Paradise
        <span className="block text-cyan-300">Under the Stars</span>
      </h2>

      <p className="mb-8 max-w-xl text-lg leading-relaxed text-slate-300 md:text-xl">
        Wake up to ocean waves, stunning sunsets, and a world-class tropical
        getaway designed for unforgettable moments.
      </p>

      <div className="flex flex-col gap-4 sm:flex-row">
        <button className="rounded-full bg-cyan-400 px-8 py-4 font-semibold text-slate-950 transition hover:bg-cyan-300">
          Reserve Your Stay
        </button>
        <button className="rounded-full border border-white/30 px-8 py-4 font-semibold backdrop-blur-md transition hover:bg-white/10">
          Explore Resort
        </button>
      </div>
    </div>
  </div>

  {/* Bottom stats */}
  <div className="absolute bottom-8 left-6 right-6 z-10 grid gap-4 rounded-3xl border border-white/10 bg-white/10 p-6 backdrop-blur-lg md:left-16 md:right-16 md:grid-cols-3">
    <div>
      <p className="text-3xl font-bold text-cyan-300">50+</p>
      <p className="text-sm text-slate-300">Luxury Villas</p>
    </div>
    <div>
      <p className="text-3xl font-bold text-cyan-300">24/7</p>
      <p className="text-sm text-slate-300">Guest Service</p>
    </div>
    <div>
      <p className="text-3xl font-bold text-cyan-300">100%</p>
      <p className="text-sm text-slate-300">Oceanfront Views</p>
    </div>
  </div>
</section>

); }

export function QuickBookingSection() { return ( <section className="bg-slate-950 px-6 py-20 text-white md:px-16"> <div className="mx-auto max-w-6xl rounded-3xl border border-white/10 bg-slate-900/80 p-8 shadow-2xl backdrop-blur-md md:p-12"> <div className="mb-10 text-center"> <p className="mb-3 text-sm uppercase tracking-[0.35em] text-cyan-300"> Plan Your Escape </p> <h3 className="text-3xl font-bold md:text-5xl">Quick Booking</h3> <p className="mx-auto mt-4 max-w-2xl text-slate-300"> Reserve your beachfront stay in just a few clicks and start counting down to your tropical getaway. </p> </div>

<form className="grid gap-6 md:grid-cols-2 lg:grid-cols-5">
      <div className="space-y-2">
        <label className="text-sm text-slate-300">Check-in</label>
        <input
          type="date"
          className="w-full rounded-2xl border border-white/10 bg-slate-800 px-4 py-3 text-white outline-none transition focus:border-cyan-300"
        />
      </div>

      <div className="space-y-2">
        <label className="text-sm text-slate-300">Check-out</label>
        <input
          type="date"
          className="w-full rounded-2xl border border-white/10 bg-slate-800 px-4 py-3 text-white outline-none transition focus:border-cyan-300"
        />
      </div>

      <div className="space-y-2">
        <label className="text-sm text-slate-300">Guests</label>
        <select className="w-full rounded-2xl border border-white/10 bg-slate-800 px-4 py-3 text-white outline-none transition focus:border-cyan-300">
          <option>1 Guest</option>
          <option>2 Guests</option>
          <option>3 Guests</option>
          <option>4+ Guests</option>
        </select>
      </div>

      <div className="space-y-2">
        <label className="text-sm text-slate-300">Room Type</label>
        <select className="w-full rounded-2xl border border-white/10 bg-slate-800 px-4 py-3 text-white outline-none transition focus:border-cyan-300">
          <option>Ocean View Villa</option>
          <option>Beach Suite</option>
          <option>Family Cottage</option>
          <option>Luxury Cabin</option>
        </select>
      </div>

      <div className="flex items-end">
        <button
          type="submit"
          className="w-full rounded-2xl bg-cyan-400 px-6 py-3 font-semibold text-slate-950 transition hover:bg-cyan-300"
        >
          Check Availability
        </button>
      </div>
    </form>
  </div>
</section>

); }

export function AboutResortSection() { return ( <section
id="about"
className="bg-slate-950 px-6 py-24 text-white md:px-16"
> <div className="mx-auto grid max-w-6xl gap-12 lg:grid-cols-2 lg:items-center"> <div className="relative"> <div className="absolute -left-6 -top-6 h-24 w-24 rounded-full bg-cyan-400/20 blur-3xl" /> <img
src="https://images.unsplash.com/photo-1500375592092-40eb2168fd21?auto=format&fit=crop&w=1200&q=80"
alt="Beach resort"
className="relative h-[520px] w-full rounded-3xl object-cover shadow-2xl"
/> </div>

<div>
      <p className="mb-4 text-sm uppercase tracking-[0.35em] text-cyan-300">
        About the Resort
      </p>
      <h3 className="mb-6 text-4xl font-bold leading-tight md:text-5xl">
        A Hidden Paradise
        <span className="block text-cyan-300">Made for Escape</span>
      </h3>
      <p className="mb-6 text-lg leading-relaxed text-slate-300">
        Nestled along pristine shores, our resort blends luxury, comfort,
        and nature into one unforgettable destination.
      </p>
      <p className="mb-8 text-lg leading-relaxed text-slate-400">
        Whether you seek adventure, romance, or peaceful rest, we create a
        stay that feels personal and memorable.
      </p>
    </div>
  </div>
</section>

); }

export function ResortExtrasSections() { const amenities = [ 'Infinity Pool', 'Beachfront Villas', 'Luxury Spa', 'Fine Dining', 'Fast Wi‑Fi', 'Private Tours', ];

const rooms = [ { name: 'Ocean View Villa', price: '$220/night' }, { name: 'Sunset Suite', price: '$180/night' }, { name: 'Family Cottage', price: '$150/night' }, ];

const activities = ['Snorkeling', 'Island Hopping', 'Bonfire Nights', 'Kayaking'];

const gallery = [ 'https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=900&q=80', 'https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?auto=format&fit=crop&w=900&q=80', 'https://images.unsplash.com/photo-1499793983690-e29da59ef1c2?auto=format&fit=crop&w=900&q=80', 'https://images.unsplash.com/photo-1522708323590-d24dbb6b0267?auto=format&fit=crop&w=900&q=80', ];

return ( <div className="bg-slate-950 text-white"> <section className="px-6 py-24 md:px-16"> <div className="mx-auto max-w-6xl"> <h3 className="mb-12 text-center text-4xl font-bold">Featured Amenities</h3> <div className="grid gap-6 md:grid-cols-3"> {amenities.map((item) => ( <div key={item} className="rounded-3xl border border-white/10 bg-slate-900 p-8 transition hover:-translate-y-2 hover:border-cyan-300/50"> <p className="text-xl font-semibold">{item}</p> </div> ))} </div> </div> </section>

<section id="rooms" className="px-6 py-24 md:px-16">
    <div className="mx-auto max-w-6xl">
      <h3 className="mb-12 text-center text-4xl font-bold">Rooms & Suites</h3>
      <div className="grid gap-8 md:grid-cols-3">
        {rooms.map((room) => (
          <div key={room.name} className="overflow-hidden rounded-3xl border border-white/10 bg-slate-900">
            <div className="h-64 bg-slate-800" />
            <div className="p-6">
              <h4 className="text-2xl font-semibold">{room.name}</h4>
              <p className="mt-2 text-cyan-300">{room.price}</p>
              <button className="mt-6 rounded-full bg-cyan-400 px-6 py-3 font-semibold text-slate-950">
                View Details
              </button>
            </div>
          </div>
        ))}
      </div>
    </div>
  </section>

  <section id="activities" className="px-6 py-24 md:px-16">
    <div className="mx-auto max-w-6xl">
      <h3 className="mb-12 text-center text-4xl font-bold">Experiences</h3>
      <div className="grid gap-6 md:grid-cols-4">
        {activities.map((activity) => (
          <div key={activity} className="rounded-3xl bg-slate-900 p-8 text-center shadow-lg">
            <p className="text-xl font-semibold">{activity}</p>
          </div>
        ))}
      </div>
    </div>
  </section>

  <section className="px-6 py-24 md:px-16">
    <div className="mx-auto max-w-6xl">
      <h3 className="mb-12 text-center text-4xl font-bold">Photo Gallery</h3>
      <div className="grid gap-6 md:grid-cols-2">
        {gallery.map((img, i) => (
          <img
            key={i}
            src={img}
            alt="Resort view"
            className="h-80 w-full rounded-3xl object-cover"
          />
        ))}
      </div>
    </div>
  </section>

  <section className="px-6 py-24 md:px-16">
    <div className="mx-auto max-w-6xl rounded-3xl border border-cyan-300/20 bg-slate-900 p-12 text-center">
      <p className="text-sm uppercase tracking-[0.35em] text-cyan-300">Special Offer</p>
      <h3 className="mt-4 text-4xl font-bold">Stay 3 Nights, Get 1 Free</h3>
      <p className="mx-auto mt-4 max-w-2xl text-slate-300">
        Book your tropical escape now and enjoy exclusive packages for couples,
        families, and groups.
      </p>
      <button className="mt-8 rounded-full bg-cyan-400 px-8 py-4 font-semibold text-slate-950">
        Claim Offer
      </button>
    </div>
  </section>

  <section id="contact" className="px-6 py-24 md:px-16">
    <div className="mx-auto grid max-w-6xl gap-10 lg:grid-cols-2">
      <div>
        <h3 className="text-4xl font-bold">Visit Our Paradise</h3>
        <p className="mt-6 text-lg text-slate-300">
          Located on a stunning beachfront with easy access to island tours,
          dining, and adventure.
        </p>
        <div className="mt-8 space-y-4 text-slate-300">
          <p>📍 Samal Island, Philippines</p>
          <p>📞 +63 900 000 0000</p>
          <p>✉️ info@azurecoast.com</p>
        </div>
      </div>
      <div className="min-h-[380px] rounded-3xl bg-slate-900" />
    </div>
  </section>

  <footer className="border-t border-white/10 px-6 py-10 text-slate-400 md:px-16">
    <div className="mx-auto flex max-w-6xl flex-col justify-between gap-4 md:flex-row">
      <p>© 2026 Azure Coast Resort. All rights reserved.</p>
      <div className="flex gap-6">
        <a href="#">Privacy</a>
        <a href="#">Terms</a>
        <a href="#">Instagram</a>
      </div>
    </div>
  </footer>
</div>

); }
