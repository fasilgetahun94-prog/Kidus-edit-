# Kidus-edit-
A website that we get a gaming news
import React, { useEffect, useMemo, useState } from "react";
import {
  Search,
  Sun,
  Moon,
  Newspaper,
  Gamepad2,
  Home,
  Mail,
  Star,
} from "lucide-react";

// --- Mock Data --------------------------------------------------------------
const TAGS = [
  "Updates",
  "PC",
  "Console",
  "Esports",
  "Guides",
  "Patch Notes",
  "Interview",
  "Tournaments",
];

const sampleArticles = {
  news: [
    {
      id: "n1",
      title: "Patch 1.2 Brings New Maps and Balance Changes",
      date: "2025-08-01",
      tags: ["Updates", "Patch Notes", "PC"],
      image:
        "https://images.unsplash.com/photo-1542751371-adc38448a05e?q=80&w=1600&auto=format&fit=crop",
      summary:
        "A major update adds two competitive maps and rebalances several hero abilities.",
      content:
        "Developers released Patch 1.2 focusing on competitive integrity. Highlights include recoil normalization, reduced stun durations, and map callout refinements.",
    },
    {
      id: "n2",
