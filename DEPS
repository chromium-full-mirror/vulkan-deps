# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '8dffe4c195918813d3aa4c557c2853e55e9ca037',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '131c5ff10f600580902229e8c2689da709e003be',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '54a521dd130ae1b2f38fef79b09515702d135bdd',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'bb86786ed9aa6576a1fb72a9eeea5203df378d9b',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '952f776f6573aafbb62ea717d871cd1d6816c387',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'c0ccad9108f811e14febfdd7cf7b4cb4537c086f',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '4b1c758046b142168a6a58dfb25d380820d8e19a',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '5f41f2a9bf3589dc5d1791d42ff46f1abe873f2b',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '751edc308040ca82052002f54bef3f0fef0f8403',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
