// === File: app/page.tsx (main app component) ===
"use client"

import { Button } from "@/components/ui/button"
import { Card, CardContent, CardHeader, CardTitle } from "@/components/ui/card"
import { Slider } from "@/components/ui/slider"
import { Play, Pause, Volume2, Radio, Loader2, Waves } from "lucide-react"
import { useFlopRadio } from "@/hooks/use-flop-radio"
import Head from "next/head"

export default function Home() {
  const { isPlaying, isLoading, volume, error, play, pause, changeVolume } = useFlopRadio()

  const handlePlayPause = () => {
    if (isPlaying) pause()
    else play()
  }

  return (
    <>
      <Head>
        <title>Internet Radio</title>
        <link rel="icon" href="/favicon.ico" />
      </Head>
      <main className="p-4 max-w-xl mx-auto">
        {/* Main Player Card */}
        <Card className="bg-gradient-to-br from-pink-400 via-pink-500 to-pink-600 text-white overflow-hidden relative">
          <div className="absolute inset-0 bg-black/20" />
          <CardContent className="p-8 relative z-10 text-center space-y-4">
            <div className="flex justify-center">
              {isLoading ? (
                <Loader2 className="h-16 w-16 animate-spin" />
              ) : isPlaying ? (
                <Waves className="h-16 w-16 animate-pulse" />
              ) : (
                <Radio className="h-16 w-16" />
              )}
            </div>

            <div>
              <h1 className="text-4xl font-bold mb-2">Internet Radio</h1>
              <p className="text-xl opacity-90 mb-1">Live Stream</p>
              <p className="text-sm opacity-75">{isPlaying ? "Now Playing" : "Ready to Play"}</p>
            </div>

            <Button
              onClick={handlePlayPause}
              disabled={isLoading}
              size="lg"
              variant="secondary"
              className="h-16 w-16 rounded-full p-0 bg-white/20 hover:bg-white/30 border-2 border-white/30"
            >
              {isPlaying ? <Pause className="h-8 w-8" /> : <Play className="h-8 w-8 ml-1" />}
            </Button>
          </CardContent>
        </Card>

        {/* Volume Control */}
        <Card className="mt-4">
          <CardContent className="p-6">
            <div className="flex items-center gap-4">
              <Volume2 className="h-5 w-5 text-muted-foreground flex-shrink-0" />
              <Slider
                value={[volume * 100]}
                onValueChange={(value) => changeVolume(value[0] / 100)}
                max={100}
                step={1}
                className="flex-1"
              />
              <span className="text-sm text-muted-foreground w-10 text-right">{Math.round(volume * 100)}%</span>
            </div>
          </CardContent>
        </Card>

        {/* Error Display */}
        {error && (
          <Card className="border-red-200 bg-red-50 mt-4">
            <CardContent className="p-4">
              <div className="flex items-center gap-2">
                <Radio className="h-4 w-4 text-red-600" />
                <p className="text-red-700 text-sm">{error}</p>
              </div>
            </CardContent>
          </Card>
        )}
      </main>
    </>
  )
}
