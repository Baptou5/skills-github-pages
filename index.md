---
title: Welcome to my blog
import Head from 'next/head';
import Header from '../components/Header';
import Shortcuts from '../components/Shortcuts';

export default function Home() {
  return (
    <div>
      <Head>
        <title>Système Qualité ISO 9001</title>
        <meta name="description" content="Système Qualité ISO 9001" />
        <link rel="icon" href="/favicon.ico" />
      </Head>
      <Header />
      <main>
        <Shortcuts />
      </main>
    </div>
  );
}
---

