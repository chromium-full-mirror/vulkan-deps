# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'deae38e25a5259cadd279b196f41feedbc521314',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'be9744eb74f522c6829c5e8d842cc29dce8259bd',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'daa093dd29aab8cbb6562b808370562f56e399fb',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '91e89a94297f63c81939023e03500031958df532',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '8c2683390a4b10c0483e3b531555dfb841e2cd84',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '299c923e47e08148a47b1df7628926cc183cb4fc',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'a3431de1d1d6259369ab8739fcbb870da11d153d',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'ba450228e2ebb4059f8a7d4bb36610464e2f0741',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '17d9a36ca369cbe74610dc039c527b4508942ee4',
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
