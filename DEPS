# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'f7c910864c67fc8a347184769b6c7bd6ae4c32ad',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'a399899a54a73e4b82cbaae7404dc1b852c29900',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'b824a462d4256d720bebb40e78b9eb8f78bbb305',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'fb7471844504abb16b732dc4fc0837119a32ec24',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '39c50d7bf094853a1f9a2e8a7e3377d425ae0c6a',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '208e174c85e33a7c05b0c1e274bbed8edca8c188',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '0a1fb7e8cb346f69862e4f12c1d7b09d23e2f84c',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'c3e5c14dfa167b50813ad7649a71287d4d4ec9db',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'c56bea31fd3951fba8bb2983ceb0c088194c8891',
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
